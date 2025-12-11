# Carte IHM CDF 1

ESP32-S3-WROOM-1 HM interface card

## IC List

- ESP32-S3-WROOM-1 (Main MCU Module)
- TLV757P (MCU 3v3 LDO)
- SSD1315 (128x64 OLED display)
- 3x WS2812B (RGB status leds)
- 74HC14 (HEX Schmitt trigger)

## Top preview

<img width="1303" height="883" alt="image" src="https://github.com/user-attachments/assets/1a765446-cbdd-4b8f-b52c-cbcd64f8e5d8" />

## Preview 3d render

<img width="1105" height="881" alt="image" src="https://github.com/user-attachments/assets/6bfbbf58-b8c2-48a3-ab0f-a83e5fa16651" />

## Pin definitions

```c
#define DIP_A_PIN 14
#define DIP_B_PIN 21
#define DIP_C_PIN 47
#define DIP_D_PIN 48

#define STARTER_PIN 11

#define TEAM_A_PIN 13
#define TEAM_B_PIN 12

#define UP_BTN_PIN 10
#define DOWN_BTN_PIN 17
#define CONF_BTN_PIN 18

#define OLED_I2C_SCL 3
#define OLED_I2C_SDA 9

#define RBG_LEDS_PIN 45

#define BATT_SENSE_PIN 2
```
