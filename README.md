# Clock Kit
 
## Project Description: 

This project creates a data visualization clock by using a Raspberry Pi and LEDs. When connected to the Internet, the Raspberry Pi can be programmed to capture real time or static data which can then be displayed on the clock face. The traditional clock face is represented with an RGB LED at each of the twelve numbers.
 
## Purpose: 

To provide the user with opportunity to learn manufacturing, electronics, programming, and research using big data.
 
## Diagrams:

![top view](top-view.png)

![side view](side-view.png)



## Software Programs: 
* CAD program, 
* Raspbian OS, 
* Python
 
## Hardware (Parts list): 
* Piece of wood (dimensions)
* 12 RGB LEDs
  * PTH Addressable https://www.sparkfun.com/products/12999
    * Raspberry Pi can not run these, so will need an Arduino interface or use
      different LEDs.
  * SMT RBG 5050 LED https://www.adafruit.com/product/619
    * These work with Raspberry Pi directly.
* Wires
* Raspberry Pi Zero W
  * microB to USB A adapter (https://www.adafruit.com/product/1099)
  * micro HDMI to HDMI adapter (https://www.adafruit.com/product/2819)
  * micro SD card (https://www.adafruit.com/product/1294)
* Micro-USB power adapter or battery pack
* Soldering Iron (optional)
* Prototyping Breadboard (optional)
 
## Tutorials and Helpful Links:
 
* Raspberry Pi Clock Python program: https://github.com/rasathus/RGBLedClock
* Code for LPD6803 module:
  * https://github.com/rasathus/pigredients/blob/master/pigredients/ics/lpd6803.py
  * https://github.com/adafruit/LPD6803-RGB-Pixels
* Code for using WS2812 LEDs with Raspberry Pi
  * https://github.com/626Pilot/RaspberryPi-NeoPixel-WS2812
  * https://tutorials-raspberrypi.com/how-to-control-a-raspberry-pi-ws2801-rgb-led-strip/
  * https://tutorials-raspberrypi.de/raspberry-pi-ws2812-ws2811b-rgb-led-streifen-steuern/
  * https://learn.adafruit.com/neopixels-on-raspberry-pi/software
* Adafruit guide to WS2812 (NeoPixel)
  * https://learn.adafruit.com/adafruit-neopixel-uberguide/overview
  * https://github.com/adafruit/Adafruit_NeoPixel
* WS2801
  * https://www.npmjs.com/package/rpi-ws2801
 
## Other clock ideas:
* http://tobiscorner.floery.net/rgb-pixel-clock-part-1/
* http://www.jeremyblum.com/2016/02/03/wordclock/
* http://iqjar.com/jar/raspberry-pi-binary-led-clock/
 

