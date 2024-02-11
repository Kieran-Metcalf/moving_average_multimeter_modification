I Like all new technology, but nothing is better or sets a better atmosphere than old vintage color string lights, so how can the micro:bit be use to prolong the life of a set of, now approaching £5 for 4 replacement lamps!

With a calbrated needle alolouge multimeter (using a resistor by reading the bands) I tested the resistances of all the lamps, I devided them into 2 sets, lamps which gave a steady resistance reading where the needle stopped for a good 10 seconds. And lamps where the needle just would not settle down. These were about 50% 50%

First as the data was dicrete as I read to the nearest Ohm I made a statistacal histogram of the results with a bin or interval of 1 Ohm and noticed a normal distribution with a median or second quartile at 50 Ohms so I chose the lamps inside the interquartile range and placed them back in the sockets of one of the 4 phase conductng wires, this, I hope will give a steady resistance to the AC an reduce the chances of the filimants burning out. 

How can this whole process be automated with the micro:pi ... With alot more steps and intergrated electronics than I anticipated. 

1. Additional hardware for resistance testing, as the micro:bit reads voltage at the pins https://learn.adafruit.com/basic-resistor-sensor-reading-on-raspberry-pi/overview
2. Conversion of this voltage measurment to an accurate resistance value, does this require callibration, no because we are only choosing the lamps in the interquartile range
3. code for a moving average for the fluxuating resistance measurments, a further average to find a single value.
4. https://stackoverflow.com/questions/14313510/how-to-calculate-rolling-moving-average-using-python-numpy-scipy
5. Push the A button to store the resistance value when it appears on the screen



> Open this page at [https://kieran-metcalf.github.io/vintage-incandescent-filimant-lamp-string-tester/](https://kieran-metcalf.github.io/vintage-incandescent-filimant-lamp-string-tester/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/kieran-metcalf/vintage-incandescent-filimant-lamp-string-tester** and import

## Edit this project

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/kieran-metcalf/vintage-incandescent-filimant-lamp-string-tester** and click import

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
