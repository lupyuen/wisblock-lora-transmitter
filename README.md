# wisblock-lora-transmitter

Arduino program that transmits 28-byte LoRa messages with [RAKwireless WisBlock](https://docs.rakwireless.com/Product-Categories/WisBlock/Quickstart/).

Configured to transmit LoRa messages to [PineDio USB](https://github.com/lupyuen/lora-sx1262) and [BL602 LoRa Firmware `sdk_app_lora`](https://github.com/lupyuen/bl_iot_sdk/blob/lorarecv/customer_app/sdk_app_lora).

NOTE: PineDio USB can receive up to 28 bytes in a message, because CH341 SPI can't transfer more than 31 bytes in a single SPI transfer.

Read the articles...

-   ["RAKwireless WisBlock talks LoRa with PineCone BL602 RISC-V Board"](https://lupyuen.github.io/articles/wisblock)

-   ["Connect PineCone BL602 to LoRa Transceiver"](https://lupyuen.github.io/articles/lora)
