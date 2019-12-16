rustypill
---------

A uniform design for my daily/IoT DIY need.

Features
========

- STM32F103CBU6/STM32F411CEU6 microcontroller (required)
- All GPIOs are available
- Support optional HD44780 LCD (or "1602", with backlight) via I2C
- Support optional ESP8266 (WiFi module), via UART serial ports
- Support optional DS3231 (accurate RTC, with battery) via I2C
- Support optional AT24Cx (EEPROM) via I2C
- Support optional microSD via SPI
- Support optional custom I2C external board (such as OLED display)
- Convenient 10-pin IDC socket (A0-A7 which supports analog input, plus GND and V5 power)
- microUSB

PCB
===

.. image:: https://github.com/Determinant/rustypill/raw/master/pcb-top.png

.. image:: https://github.com/Determinant/rustypill/raw/master/pcb-bottom.png

