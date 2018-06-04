## ATtiny I2C FRAM Driver

[This driver is for the Adafruit I2C FRAM breakout.](http://www.adafruit.com/products/1895)
[Modified from the original Adafruit FRAM I2C library.](https://github.com/adafruit/Adafruit_FRAM_I2C)
[TinywireM is required.](https://github.com/adafruit/TinyWireM)

# Modifications

The original library from Adafruit did not support the Attiny due to it's use of Wire.h. To correct this I simply switch Wire.h out for TinywireM.h. The library can be used in the same way that one would use the original library. 

Tested using the Attiny85.

pin #0 is SDA (I2C data), pin #2 is SCK (I2C clock).