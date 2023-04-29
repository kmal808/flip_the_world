## HC-SR04 Ultrasonic Distance Sensor

Plugin by Sanqui: https://github.com/Sanqui/flipperzero-firmware/blob/hc_sr04/applications/hc_sr04/hc_sr04.c

![HC-SR04](https://user-images.githubusercontent.com/57457139/182779625-f3d43727-c9a6-4c44-8916-3150cccb0fc8.jpg)

```
HC-SR04: 1 (RX0) -> FZ: 13 or 15 (these are TX pins)
HC-SR04: 2 (TX0) -> FZ: 14 or 16 (these are RX pins)
HC-SR04: 3 (GND) -> FZ: 8 or 11 or 18 (GND)
HC-SR04: 4 (5V)  -> FZ: 1 (5V)

Switch between UART Pins 13/14 and 15/16 setting in:
Flipper -> GPIO -> USB-UART Bridge -> LEFT -> UART Pins
```

![HC-SR04](https://user-images.githubusercontent.com/57457139/208268156-05021579-5410-44bc-a705-99fc97b0d046.png)

---

## NMEA 0183 GPS

https://github.com/ezod/flipperzero-gps

```
GPIO pins 9 (3.3V), 11 (GND), 13 (TX), and 14 (RX)
```

![GPS NMEA 0183](https://github.com/ezod/flipperzero-gps/raw/main/wiring.png)

---

## i2c Tools (by NaejEL)

```
C0 -> SCL / C1 -> SDA / GND -> GND | 3v3 logic levels only!
```

https://github.com/NaejEL/flipperzero-i2ctools

---

## HTU21D / SI7021 Temperature Sensor

![HTU21D](https://user-images.githubusercontent.com/57457139/208267976-6709577e-f15d-4ec0-928d-dcff9b3389be.png)

```
GPIO pins 9 (3.3V), 11 (GND), 15 (sda), and 16 (scl)
```

https://github.com/Mywk/FlipperTemperatureSensor
![Temperature Sensor - HTU21D / SI7021](https://github.com/Mywk/FlipperTemperatureSensor/raw/master/images/Flipper.png)

---

## AM2320/AM2321 Temp. Sensor

```
GPIO pins 9 (3.3V), 11 (GND), 15 (sda), and 16 (scl)
```

https://github.com/xMasterX/AM2320_Flipper_Plugin
![Connection](https://user-images.githubusercontent.com/10697207/199586577-5c9cf516-2096-4d70-9e2f-1f9458a68d65.jpg)

---

## DHT11/22 Temp. Sensor

```
VCC (none, +, VCC, red wire)	1 (5V) or 9 (3V3)
GND (-, GND, black wire)	8, 18 (GND)
DATA (OUT, S, yellow wire)	2-7, 10, 12-17 (to choose from)
```

## https://github.com/quen0n/FipperZero-DHT-Monitor
