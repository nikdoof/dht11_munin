RPi DHT11 Munin Plugins
=======================

Two simple Munin plugins that allow you to monitor the values returned from a DHT11 temperature and humidity module connected to a Raspberry Pi

Requirements
------------

* [Adafruit_DHT](https://github.com/adafruit/Adafruit_Python_DHT)
* [python-munin](https://github.com/samuel/python-munin)

Munin Configuration
-------------------

These values will be set in your ```plugin-conf.d/munin-node``` file.

* ```dht11_pin``` - The GPIO pin on the Raspberry Pi where the DHT11 data line is connected.

Example Config
--------------

    [dht11*]
    user root
    env.dht11_pin 2
