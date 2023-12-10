# BTCticker
## ESP8266WiFi and Adafruit_SSD1306 BTC Ticker, currently supports USD and GBP currencies.
This device code is designed to run on an ESP8266 paired with an Adafruit_SSD1306 using the Ardunio flashing tool to flash the relevant board. Arduino uses a variant of the C++ programming language. The code is written in C++ with an addition of special methods and functions. Moreover, when you create a 'sketch', it is then processed and compiled to machine code for the microcontroller of your choice which is specified in the Arduino environment, it is worth noting that you must keep your board up to date via the Ardunio board manager else some functions may return an error and create compile time errors.<br><br>
<p align="center">
<img src="https://github.com/Lee-88/BTCticker/assets/52921992/fd889d41-ecb5-41e9-8871-14cbc385ff08"></img>

</p><br><br>

## Required Libraries
(Install via 'Sketch->Include Library->Manage Libraries' or using the hotkey 'CTRL+SHIFT+I')
+ <ESP8266WiFi.h>                                  
+ <ArduinoJson.h> <br>
+ <Wire.h> <br>
+ <Adafruit_GFX.h> <br>
+ <Adafruit_SSD1306.h> <br>
<br>

## Wire Diagrams for ESP8266Wifi and ESP8266MOD mini
![btcticker](https://github.com/Lee-88/BTCticker/assets/52921992/82e21098-cac1-4778-a239-215f4b4d3034)


### Known Bugs
+ exchange rate not fixed to markets
+ +100,000.00 per BTC not supported.

### Fixed Bugs
+ no answer from API resulted in no price to be displayed on ticker.
+ GBP price clips on occation incorrectly due to length of the JSON object collected via the coinbase API.

### Future Support
+ Adafruit LCD TFT 128X160 1.8
<br><br>

