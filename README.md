# Esp32-Sprinkler

## ESP8266 OpenSprinkler ported to ESP 32  

This is a very first version of the well known OpenSprinkler firmware ported from Esp8266 to Esp32.

The code can be compiled using github.com/espressif/esp32-arduino core libraries and run on any ESP32 board.
It require same hw configuration as ESP8266 version.

In this initial version some essential libraries is still missing like WiFiManager and Ping libraries. 
I added some temporary shortcut to allow the code to compile and run (e.g. hardcoded wifi SSID andd password).

I encourage anybody interested to build the code and test it to help me on this debug phase!
