ESP32-WROOM

![ESP32-WROOM](https://user-images.githubusercontent.com/57457139/182290985-54d00e1e-dd3f-4efd-a66f-4d6b8e8c2ed2.jpg)

NOTE: Use `old_hardware.bin` if flashing Marauder onto the ESP32-WROOM (thanks wyldgoat!)<br>
[Easy Flasher (Windows / Linux / Mac) available here](https://github.com/UberGuidoZ/Flipper/tree/main/Wifi_DevBoard/FZ_Marauder_Flasher/ESP32-WROOM).

![wyldgoat](https://user-images.githubusercontent.com/57457139/182552144-46abf993-160e-42e2-8dde-466da146b16d.png)<br>
![bobo_dudu](https://user-images.githubusercontent.com/57457139/182552153-9c50f817-8b8c-4d31-8d62-3fe8fca7a48b.png)

## ESP32 / ESP32-WROOM Pinout to Flipper Zero

(Thanks [E_Surge](https://github.com/ESurge) and wyldgoat for guidance!)<br>
NOTE: Make sure you're using at least an ESP32 v2 or above for full functionality! [Good read](https://blog.spacehuhn.com/esp32-deauther).<br>
Running an ESP32 single-core and want Marauder? You've gotta head over to [V0lk3n's write-up](https://github.com/V0lk3n/Flipper-ESP32-Solo-Marauder)!

ESP32: 3 (RX0) -> FZ: 13 or 15 (these are TX pins)<br>
ESP32: 1 (TX0) -> FZ: 14 or 16 (these are RX pins)<br>
ESP32: GND -> FZ: 8 or 11 or 18 (GND)<br>
ESP32: 5V -> FZ: 1 (5V) **_OR_** ESP32: 3.3V -> FZ: 9 (3.3V)<br>
_NOTE: Make sure to enable 5v under GPIO on the Flipper_

Switch between UART Pins 13/14 and 15/16 setting in FlipperZero<br>
`(GPIO -> USB-UART Bridge -> LEFT -> UART Pins)`
