# Cosmic LoRa Pulse

## Overview

Cosmic LoRa Pulse is an Entry-Level Development Board that will fasten your time to market or ease your DIY project. It has the smallest form factor all of Cosmic LoRa Development Board line up. Hence, you can reside this board in the dimension-constrained spot. It is also armed with a low-power microcontroller ATMega 328 with Pro Mini bootloader just like [Cosmic LoRa Ray](https://github.com/farizalemuda/cosmic-lora-ray). The low-power feature then amplified with the selection of 8 MHz crystal clock to make it consume less power. Furthermore, the board works with 3.3V which can be found on rechargeable LiPo battery and solar panel. Hence, Cosmic LoRa Pulse already had the on-board charging module with USB as the source. Speaking about the connectivity as part of the a-must IoT capability, the board equipped with LoRa(WAN) module of [RFM95W](https://cdn.sparkfun.com/assets/learn_tutorials/8/0/4/RFM95_96_97_98W.pdf). LoRa(WAN) has a good reputation for low power consumption, making this board even more useful in a low power ecosystem. In conclusion, this is the most go-to board for your IoT applications.

> Cosmic are universe so our products name are based on universe.

[Dokumentasi dalam bahasa Indonesia](id/)

## Technical Spesification

On-going

## Documentation

### Pinout Diagram

On-going

### LoRa(WAN) Chip Interfacing

| Cosmic LoRa Ray   | RFM95W |  
|-------------------|------- |
| D11               | MOSI   |
| D12               | MISO   |
| D13               | SCK    |
| D10               | NSS    |
| D9                | RST    |
| D2                | DIO0   |
| D6                | DIO1   |
| D7                | DIO2   |

### Examples

#### LoRa Point-to-Point

* [Receiver](examples/LoRa_P2P_Receiver/LoRa_P2P_Receiver.ino)
* [Transmitter](examples/LoRa_P2P_Transmitter/LoRa_P2P_Transmitter.ino)

#### LoRaWAN

* [ANTARES](examples/LoRaWAN_ANTARES/LoRaWAN_ANTARES.ino)

## FAQ

On-going
