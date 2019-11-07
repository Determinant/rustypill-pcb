rustypill
---------

A uniform design for my daily/IoT need.

Features
========

- STM32F103C8Tx microcontroller (required)
- All GPIOs are available
- Support optional HD44780 LCD (or "1602", with backlight)
- Support optional ESP8826 (WiFi module), via UART serial ports
- Support optional DS3231 (accurate RTC, with battery), via I2C
- Support optional AT24Cx (EEPROM), via I2C
- Convenient 10-pin IDC socket (A0-A7 which supports analog input, plus GND and V5 power)
- Micro USB

PCB
===

.. image:: https://raw.githubusercontent.com/Determinant/rustypill/master/pcb-top.png

.. image:: https://raw.githubusercontent.com/Determinant/rustypill/master/pcb-bottom.png
