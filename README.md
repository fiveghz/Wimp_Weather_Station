Wimp Weather Station & Lightning Sensor
=========================

[![Wimp Weather Station](https://cdn.sparkfun.com/r/600-600/assets/learn_tutorials/2/1/7/Setup-4.jpg)](https://cdn.sparkfun.com/assets/learn_tutorials/2/1/7/Setup-4.jpg)

[*A wireless weather station based on the Electric Imp*](https://learn.sparkfun.com/tutorials/weather-station-wirelessly-connected-to-wudnerground)

The Wimp is a personal weather station that uses the [weather shield](https://www.sparkfun.com/products/12081) along with an [Electric Imp](https://www.sparkfun.com/products/11395) to push live weather data up to [Wunderground](http://www.wunderground.com/). You can help increase the accuracy and prediction of weather by adding a weather meter to your house! But why buy an off-the-shelf system when you can build you own? For around $250 you can build a cutting edge open source station that you have complete control over! All you need is a pile of parts and access to a Wifi network.

Read the tutorial on how to setup your own [weather station wirelessly connected to Wunderground](https://learn.sparkfun.com/tutorials/weather-station-wirelessly-connected-to-wudnerground).

This particular project uses an [AS3935 lightning sensor module](http://www.embeddedadventures.com/as3935_lightning_sensor_module_mod-1016.html) from [Embedded Adventures](http://www.embeddedadventures.com/).

Pinouts should be as follows:
  GND   GND
  MOSI  11
  MISO  12
  SCLK  13
  IRQ   4
  SI    GND
  CS    10

Repository Contents
-------------------

The sketch to be loaded onto the Arduino is called *Wimp_Weather_Station.ino*. The Squirrel code that goes on the electric imp is called *agent.nut* and *device.nut* for the two parts of Imp code.

License Information
-------------------
The hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
The code is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Distributed as-is; no warranty is given.
