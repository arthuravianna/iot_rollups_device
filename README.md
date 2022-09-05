# IoT Rollups Device
This repository contains the specifications, code and hardware, used by the devices in the DApp developed using the Cartesi Rollups. The DApp repository can be accessed using this [link](https://github.com/ArtV97/iot_rollups_dapp).

## Hardware
- Arduino Uno
- NEO-6M GPS Module ([Datasheet](https://content.u-blox.com/sites/default/files/products/documents/NEO-6_DataSheet_%28GPS.G6-HW-09005%29.pdf))
- MicroSD Module
- Protoboard
- Jumpers

## Extra Libraries
- [TinyGPS](https://www.arduino.cc/reference/en/libraries/tinygps/)

## Wiring Diagram
![Wiring](wiring.png)

### NEO-6M GPS Module
| Module Pin | Arduino Pin |
| -----------|-------------|
| VCC | 5V |
| RX | Pin 9 |
| TX | Pin 8 |
| GND | GND |
### MicroSD Module
| Module Pin | Arduino Pin |
| -----------|-------------|
| CS | Pin 10 |
| SCK | Pin 13 |
| MOSI | Pin 11 |
| MISO | Pin 12 |
| VCC | 5V |
| GND | GND |
