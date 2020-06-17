# PersonalWeatherStation
Personal Weather Station with Arduino, a smart device for [Pixel Weather v4.x](https://apps.apple.com/app/id1278650505). https://github.com/woointeractive/PersonalWeatherStation



## Table of contents
- [1. Features and Screen](#1)
- [2. Board and Parts](#2)
- [3. Design Picture](#3)
- [4. Pin Table](#4)
- [5. Driver](#5)
- [6. Firmware](#6)
- [7. App Download](#7)


**1. Features and Screen:**

- Temperature and humidity
- Clcok with temperature and humidity
- Pomodoro Timer
- Game

![](/image/v1.0.0_OLED.png)


**2. Board and Parts:**

- Arduino Uno or Nano
- Bluetooth with CC2541 (VCC, GND, TX, RX)
- OLED 128x64 IIC(I2C) with SSD1306 (VCC, GND, SDA, SCL)
- Passive Buzzer (3.3v, GND, S or D)
- DHT11 (VCC, GND, S or D)


**3. Design Picture:**

Arduino Uno

![](/image/v1.0.0_Uno.png)

Arduino Nano

![](/image/v1.0.0_Nano.png)


**4. Pin Table:**

Arduino Uno / Nano Pin | Part Pin | Part Name |
:-: | :-: | :-: |
VCC | VCC | Bluetooth |
GND | GND| Bluetooth |
RX | TX| Bluetooth |
TX | RX| Bluetooth |
VCC | VCC| OLED |
GND | GND| OLED |
A4 | [SDA](https://www.arduino.cc/en/Reference/Wire)| OLED |
A5 | [SCL](https://www.arduino.cc/en/Reference/Wire)| OLED |
3.3v | 3.3v| Passive Buzzer |
GND | GND| Passive Buzzer |
D13 | S or D| Passive Buzzer |
VCC | VCC| DHT11 |
GND | GND| DHT11 |
D2 | S or D| DHT11 |


**5. Driver:**

[macOS](/driver/CH34x_Install_V1.5.pkg) - Serial port driver for Sierra (10.12) and High Sierra (10.13)


**6. Firmware:**

[HelloWorld](/firmware/HelloWorld.hex.zip) - Testing screen and buzzer

[v1.0.0](/firmware/v1.0.0.hex.zip) - Include all functions


**7. App Download:**

[Pixel Weather v4.0.0](https://apps.apple.com/app/id1278650505) (Available on App Store, for iPhone, iPad, Watch)
