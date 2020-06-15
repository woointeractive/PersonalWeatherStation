# PersonalWeatherStation
Personal Weather Station with Arduino, a smart device for Pixel Weather v4.x


**v 1.0.0**

**Features and Screen:**

1. Temperature and humidity
2. Clcok with temperature and humidity
3. Pomodoro Timer
4. Game

![](/images/v1.0.0_OLED.png)


**Board and Parts:**

- Arduino Uno or Nano
- Bluetooth with CC2541 (VCC, GND, TX, RX)
- OLED 128x64 IIC(I2C) with SSD1306 (VCC, GND, SDA, SCL)
- Passive Buzzer (3.3v, GND, S or D)
- DHT11 (VCC, GND, S or D)


**Design Picture:**

Arduino Uno

![](/images/v1.0.0_Uno.png)

Arduino Nano

![](/images/v1.0.0_Nano.png)


**Pin Table:**

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


**Firmware:**

[HelloWorld](/firmware/HelloWorld.hex.zip) - Testing screen and buzzer

[v1.0.0](/firmware/v1.0.0.hex.zip) - Include all functions


**App available on App Store**

[Pixel Weather v4.0.0](https://apps.apple.com/app/id1278650505) (iPhone, iPad, Watch)