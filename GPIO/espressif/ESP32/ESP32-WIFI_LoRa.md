# LoRa ESP32 Wifi (Wifi + Bluetooth + LoRa 433 MHz)

![WIFI_LoRa_ESP32 to F0](https://user-images.githubusercontent.com/57457139/182568878-aef3ff21-2748-4ba3-9cdd-bc2f5d33b26d.jpg)

## LoRa ESP32 Wifi Pinout to Flipper Zero

LoRa32: 1 (RX0) -> FZ: 13 or 15 (these are TX pins)<br>
LoRa32: 2 (TX0) -> FZ: 14 or 16 (these are RX pins)<br>
LoRa32: 3 (GND) -> FZ: 8 or 11 or 18 (GND)<br>
LoRa32: 4 (3.3V) -> FZ: 9 (3.3V)

Switch between UART Pins 13/14 and 15/16 setting in FlipperZero<br>
`GPIO -> USB-UART Bridge -> LEFT -> UART Pins`
