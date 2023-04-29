# Raspberry Pi Zero UART

![Rpi_Zero_GPIO](https://user-images.githubusercontent.com/22322762/183289015-45329e9c-83e0-4483-96a0-1b68552bfa3f.png)

## Raspberry Pi Zero : Prerequisite

Mount your SD Card to your computer and add the following line at the end of `/boot/config.txt` file.

`enable_uart=1`

Additionally you can look at the baudrate in the `/boot/cmdline.txt` file, which should be `115200` by default.

## Raspberry Pi Zero : Pinout to Flipper Zero

```
PiZero: 4 (5V) -> FZ: 1 (5V)
PiZero: 6 (GND) -> FZ: 11 (GND)
PiZero: 8 (UART0_TXD) -> FZ: 14 (RX)
PiZero: 10 (UART0_RXD) -> FZ: 13 (TX)
```
