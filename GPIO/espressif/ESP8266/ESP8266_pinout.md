# ESP8266

![ESP8266](https://user-images.githubusercontent.com/57457139/182291241-8728052d-aa33-46b0-8e3d-fe44bbda4b6b.jpg)

If you have the ESP8266 and are looking to use a wifi deauth, check out [speexvocon's](https://github.com/Speexvocon/FlipperZeroESPexpansion) easy [web flasher](https://github.com/Speexvocon/FlipperZeroESPexpansion#programming-the-module)!<br>
If you're looking to give another deauther a try, [check out HEX0DAYS repo over here](https://github.com/HEX0DAYS/FlipperZero-PWNDTOOLS).

## ESP8266 Pinout to Flipper Zero

(Thanks PixelHerstel for additional guidance!)

ESP8266: 1 (TX0) -> FZ: 14 or 16 (these are RX pins)<br>
ESP8266: 3 (RX0) -> FZ: 13 or 15 (these are TX pins)<br>
ESP8266: 5 -> FZ: 7<br>
ESP8266: 6 -> FZ: 6<br>
ESP8266: 7 -> FZ: 5<br>
ESP8266: 8 -> FZ: 4<br>
ESP8266: VIN -> FZ: 1<br>
ESP8266: GND -> FZ: 8 or 11 (GND)<br>
FZ: 16 -> FZ: 18 (yes, FZ to FZ)<br>
ESP8266: 5V -> FZ: 1 (5V)<br>
_NOTE: Make sure to enable 5V under GPIO on the Flipper_<br>
**_OR_** ESP32: 3.3V -> FZ: 9 (3.3V) though this can have issues...

Switch between UART Pins 13/14 and 15/16 setting in FlipperZero<br>
`(GPIO -> USB-UART Bridge -> LEFT -> UART Pins)`

A visual pinout can be seen in [this PDF](https://github.com/UberGuidoZ/Flipper/blob/main/GPIO/ESP8266_WIFI_Schematic.pdf), too.
