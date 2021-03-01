# TinyWeatherStation
This is an open sourced small weather station that are able to retrieve data from Open Weather and display it on TFT LCD Screen. Powered with Hibiscus Sense by Myduino

To install, you can refer to the Wiki section of this repository and the steps are in order. [Wiki](https://github.com/NaimFuad/TinyWeatherStation/wiki)

![](https://github.com/NaimFuad/TinyWeatherStation/blob/main/Image/TinyWeather%20Thumbnail.jpg)
![](https://github.com/NaimFuad/TinyWeatherStation/blob/main/Image/Weather%20Station%20RIGHT.png)

## Features

Display weather data from OpenWeather such as current weather, temperature , humidity , wind direction , air pressure and visibility. The RGB lighting will change based on current weather.

## Hardware

1. Hibiscus Sense ESP32 IoT Developtment Board - [Cytron](https://my.cytron.io/p-hibiscus-sense-esp32-iot-development-board?search=hibiscus&description=1) or [Myduino](https://myduino.com/product/myd-036/)
2. 1.8-inch 128x160 TFT LCD Breakout (ST7735) - [Cytron](https://my.cytron.io/p-1.44-inch-128x128-tft-lcd-breakout-st7735?search=st7735&description=1)
3. Female-Female Jumper Wire - [Cytron](https://my.cytron.io/p-40-ways-female-to-female-jumper-wire?search=jumper%20wire&description=1)
4. 3D Printed Enclosure - [Thingiverse](https://www.thingiverse.com/thing:4779789)
5. Type C USB Cable for programming and power supply

## Software

1. Arduino IDE

## Library Used
1. NTPClient         -   Date/Time manager 
2. WiFi.h            -   Wifi Configuration
3. WiFiUdp           -   Library to send and receive UDP messages
4. WiFiClient        -   Driver for WiFi client
5. ArduinoJson       -   Arduino Json to parse request into JSON object. Installed version 5.13, last version is not compatible.
6. Adafruit_GFX      -   LCD graphical driver
7. TFT_eSPI          -   Graphics and font library for ST7735 driver chip
8. SPI               -   SPI connection
9. SPIFFS            -   Serial Peripheral Interface Flash File System to store and retrieve data on ESP
10. Adafruit_NeoPixel -   RGB Lighting

## Hardware Wiring

* GND - GND
* VCC - 3.3V
* SCL - GPIO18
* SDA - GPIO19
* RES - GPIO04
* DC - GPIO02
* CS - GPIO15
* BLK - 3.3V

## Hibiscus Sense ESP32 IoT Developtment Board  Overview

![Hibiscus Sense Overview](https://github.com/NaimFuad/TinyWeatherStation/blob/main/Image/Hibiscus-Sense-V1.0-Overview.jpg)
