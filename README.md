# PersonalWeatherStation
Personal Weather Station with Arduino, a smart device for [Pixel Weather v4.x](https://apps.apple.com/app/id1278650505).
  
  

## Table of contents
- [1. Features and Screenshots](#1-features-and-screenshots)
- [2. Board and Parts](#2-board-and-parts)
- [3. Design Pictures](#3-design-pictures)
- [4. Pin Table](#4-pin-table)
- [5. Drivers](#5-drivers)
- [6. Firmwares](#6-firmwares)
- [7. App Download](#7-app-download)
  


#### **1. Features and Screenshots:**

- Temperature and humidity
- Clcok with temperature and humidity
- Pomodoro Timer
- Game

    ![](/images/v1.0.0_OLED.png)
  


#### **2. Board and Parts:**

- Arduino [Uno](https://store.arduino.cc/usa/arduino-uno-rev3) or [Nano](https://store.arduino.cc/usa/arduino-nano)
- Bluetooth with CC2541 (VCC, GND, TX, RX)
- OLED 128x64 IIC(I2C) with SSD1306 (VCC, GND, SDA, SCL)
- Passive Buzzer (3.3v, GND, S or D)
- DHT11 (VCC, GND, S or D)
  


#### **3. Design Pictures:**

- **Arduino Uno**

    ![](/images/v1.0.0_Uno.png)

- **Arduino Nano**

    ![](/images/v1.0.0_Nano.png)
  


#### **4. Pin Table:**

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
  


#### **5. Drivers:**

[macOS](/drivers/CH34x_Install_V1.5.pkg) - Serial port driver for Sierra (10.12) and High Sierra (10.13)
  


#### **6. Firmwares:**

[HelloWorld](/firmwares/HelloWorld.hex.zip) - Testing screen and buzzer

[v1.0.0](/firmwares/v1.0.0.hex.zip) - Include all functions
  


#### **7. App Download:**

[Pixel Weather v4.x](https://apps.apple.com/app/id1278650505) (Available on App Store, for iPhone, iPad, Watch)
