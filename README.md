# PersonalWeatherStation
Personal Weather Station with Arduino


**v 1.0.0**

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

[v1.0.0](/firmware/v1.0.0.hex.zip)


