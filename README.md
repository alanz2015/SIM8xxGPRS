Folked from Seeeduino GPRS, do some modification to be compatible to SIM868 GPS/GPRS module.

## SIM868 GPRS/GPS Module

![](./mega2560_sim868.jpg)

## Connection Diagram

![](./ARDUINO连接图.png)

NOTE: The serial port connection between this SIM868 module and MEGA2560 is based hardware UART, Serial2 for GPS, and Serial3 for GPRS. So far the examples/Serial, GPRS_HTTP, and GPRS_SMS have been modifed and work with the attached SIM868 module (Chinese vendor). The power supply to SIM868 module MUST be 7~12V (1A at least).
