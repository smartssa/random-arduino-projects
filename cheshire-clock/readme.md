A small project using:

* RTC library: https://github.com/adafruit/RTClib
* NeoPixel library: https://github.com/adafruit/Adafruit_NeoPixel
* Modifications to the code found in the 60 pixel clock; https://learn.adafruit.com/neopixel-60-ring-clock to use different LED configurations.


Parts:
* 1 x Arduino UNO
* 1 x 12 pixel ring; http://www.adafruit.com/products/1643
* 2 x 15 pixel quarter sticks; http://www.adafruit.com/products/1768
* 1 x DS1307 RTC kit; http://www.adafruit.com/products/264
* breadboard
* wire

Notes:
The fritzing diagram includes 3x rings since the quarter sticks weren't in the graphics library (yet)

The Arduino sketch should be easily adaptable to use any configuration of neopixels to display time in various methods.

The clock powers off of USB without any (apparent) issues.

A photo:
http://instagram.com/p/rM-UqUFOY1
