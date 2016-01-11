# Adafruit_SSD1306
<!-- START COMPATIBILITY TABLE -->

## Compatibility

MCU               | Tested Works | Doesn't Work | Not Tested  | Notes
----------------- | :----------: | :----------: | :---------: | -----
Atmega328 @ 16MHz |             |             |     X       | 128x32 I2C &amp; SPI works!
Atmega328 @ 12MHz |             |             |     X       | I2C 128x32 works!
Atmega32u4 @ 16MHz |             |             |     X       | I2C 128x32 works!
Atmega32u4 @ 8MHz |             |             |     X       | I2C 128x32 works!
ESP8266           |             |             |     X       | I2C 128x32 works, change OLED_RESET to different pin if using default I2C pins D4/D5.
Atmega2560 @ 16MHz |             |             |     X       | I2C 128x32 works!
ATSAM3X8E         |             |             |     X       | I2C 128x32 works!
ATSAM21D          |             |             |     X       | I2C 128x32 works!
ATtiny85 @ 16MHz  |             |      X       |            | 
ATtiny85 @ 8MHz   |             |      X       |            | 

  * ATmega328 @ 16MHz : Arduino UNO, Adafruit Pro Trinket 5V, Adafruit Metro 328, Adafruit Metro Mini
  * ATmega328 @ 12MHz : Adafruit Pro Trinket 3V
  * ATmega32u4 @ 16MHz : Arduino Leonardo, Arduino Micro, Arduino Yun, Teensy 2.0
  * ATmega32u4 @ 8MHz : Adafruit Flora, Bluefruit Micro
  * ESP8266 : Adafruit Huzzah
  * ATmega2560 @ 16MHz : Arduino Mega
  * ATSAM3X8E : Arduino Due
  * ATSAM21D : Arduino Zero, M0 Pro
  * ATtiny85 @ 16MHz : Adafruit Trinket 5V
  * ATtiny85 @ 8MHz : Adafruit Gemma, Arduino Gemma, Adafruit Trinket 3V

<!-- END COMPATIBILITY TABLE -->