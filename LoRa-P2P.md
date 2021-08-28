# LoRa Point to Point

[back](../)

## Topology

On-going

## Requirements

* 2x [Cosmic LoRa Pulse](https://www.tokopedia.com/cosmic-iot/lora-arduino-development-board-915-mhz-915mhz-antenna-lora-pulse-v1)
* 2x Micro USB Type B Cable
* [Arduino IDE](https://www.arduino.cc/en/software)

## Source Codes

* [Transmitter](examples/LoRa_P2P_Transmitter/LoRa_P2P_Transmitter.ino)
* [Receiver](examples/LoRa_P2P_Receiver/LoRa_P2P_Receiver.ino)

## Step by Step

1. Plug the Cosmic LoRa Pulse boards to your Laptop.
2. COM Port should be activated. ([If not? Install driver](https://sparks.gogo.co.nz/ch340.html)).
3. Setup in Arduino IDE :
   * Pick the appropriate board : Tools -> Board -> Arduino Pro or Pro Mini
   * Pick the appropriate processor : Tools -> Board -> ATMega 328P (3.3V 8 MHz)
4. Load [Transmitter code](examples/LoRa_P2P_Transmitter/LoRa_P2P_Transmitter.ino) to Arduino IDE.
5. Click Verify then Click Upload to Board.
6. Open Serial Monitor of Arduino IDE. Set the Baud Rate as stated in Serial.begin of the transmitter code. Some debug info should be appeared stated it transmits some data.
7. Load [Receiver code](examples/LoRa_P2P_Receiver/LoRa_P2P_Receiver.ino) to Arduino IDE.
8. Click Verify then Click Upload to Board.
9. Open Serial Monitor of Arduino IDE. Set the Baud Rate as stated in Serial.begin of the receiver code. Some debug info should be appeared stated it recieves some data.
10. YEEAAYY!! You are sending LoRa Point-to-Point.
