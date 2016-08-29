TCS34725_Color_Sensor
=====================
The TCS34725 is an RGB color sensor from Adafruit. It was used for line-sensing
in the R2-D2 robot I worked with in Cornell Cup. The sensor has a white light
source and measures the potential across photodiodes with red, green and blue
filters in response to reflected light. These measurements can be read via an
I2C interface.

Adafruit provides an Arduino library for interfacing with the sensor. While the
Intel Edison can run Arduino code, new C-based firmware had to be written for
integration with pre-existing firmware on the Intel Edison. 
