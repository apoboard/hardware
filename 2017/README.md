2017 Propagand-Eye
=======================================
<p align="center">
<img src = "http://openponics.com/imgs/apoboard2017.jpg">
</p>

This board uses an Atmega328p microcontroller (the same device in the Arduino Uno) and can be programmed with an FTDI serial adapter and the Arduino IDE. There is a DC/DC boost-converter (the PAM2401) to provide 5 volts from a single AA battery. On board are 10 addressable WS2812 LEDs (the same LEDs used on all Neopixel products). There is also an infrared (IR) transmitter/receiver pair that allows the boards to communicate with one another. A tactile button is also provided to switch through modes.

Hacking Your Eyeball
=======================================
This section will cover all the information you'll need to start hacking your eye via hardware.

Arduino IDE Settings
----------------------
* Arduino IDE Version - 1.6.8
* Board - Arduino Uno
* Baud Rate - 115200

Hardware Pin connections
------------------
* Button Pin - D2
* WS2812 LED Pin - D7
* IR_RX Pin - D8
* IR_TX Pin - D9

Assembly Instructions
-------------------
<p align="center">
<img src = "https://cdn.sparkfun.com/assets/home_page_posts/2/3/9/8/AssemblyInstructions.png">
</p>


See the [Software README](https://github.com/apoboard/software/blob/master/2017/README.md) for more info. 

License Information
-------------------

All of these files are developed for free, for Apogaea, and for fun. It is publicly available under the GNU General Public License version 2 (the "GPL License"). For more information, please see: http://www.gnu.org/licenses/gpl-2.0.html

Copyright (c) John English, Joel Bartlett, 2017 Licensing: GPL v2
