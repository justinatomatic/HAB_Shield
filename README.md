HAB Shield
==========

HAB shield is an Arduino shield for creating a HAB (High Altitude Ballooning) tracker. 

The shield is designed around the following components. 

* [Radiometrix NTX2 Transmitter](http://ava.upuaut.net/store/index.php?route=product/category&path=71_63)
* [u-Blox GPS](https://www.sparkfun.com/products/9436) *Warning 3.3 Volt*
* [OpenLog](https://www.sparkfun.com/products/9530)
* [One Wire Digital Temperature Sensors - DS18B20](https://www.sparkfun.com/products/245)
* MOSFET based cutdown

These boards where built for a project and I have a few extra that I don't need.

The NTX2 Transmitter circuit is straight from the UKHAS guide to using the [NTX2 with Arduino](http://ukhas.org.uk/guides:linkingarduinotontx2).

We build 15 trackers using the Sparkfun [Arduino Pro 328 - 3.3V/8MHz](https://www.sparkfun.com/products/10914) with everthing at 3.3 volt.  You could use a regular 5 volt arduino if you had a [5v compatible GPS](http://ava.upuaut.net/store/index.php?route=product/category&path=59_60)

Note the cutdown sections has never been populated and tested. YMMV

At 3.3V/8Mhz we had some timeing issues with software serial on the GPS are reverted to using the hardware UART for the GPS.

All credit to the [UKHAS](http://ukhas.org.uk/) for everthing thay give to the HAB community. Read their guides and fly safe. 
