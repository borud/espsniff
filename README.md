# About this code

This is just some test-code I wrote quickly to see if I could use the
ESP8266 to sniff WiFi frames.  I put it here in case someone might
find it useful.

# Prerequisites

This uses the Arduino IDE and you need to install support for the
ESP8266.  You can do this by first going into the preferences pane and
adding http://arduino.esp8266.com/stable/package_esp8266com_index.json
to the setting that says **"Additional Boards Manager URLs"**.

Then you have a look under **Tools > Boards > Board Manager** and do a
search for ESP8266 and install the package for supporting ESP8266
devices.

# Documentation

If you find the ESP8266 interesting and want to learn more I would
suggest having a look at the official documentation of Neil Kolban's
book on the ESP8266.

  - [ESP8266 Arduino Core](http://esp8266.github.io/Arduino/versions/2.3.0/)
  - [Neil Kolban's ESP8266 book (free)](http://neilkolban.com/tech/esp8266/)

# Where to get the ESP8266

I get my ESP8266 units either from [Adafruit](http://adafruit.com/) or
[Aliexpress](http://aliexpress.com/).

*Be aware that if you buy the devices on Aliexpress you have to make
sure that the USB-to-UART chip that are on these boards will work with
your computer.  If you have a Mac there are some chips that won't work
(can't remember which right now).  If you want to be safe I'd go for
Adafruit since they usually do a good job choosing decent components.*
