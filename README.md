## Zio nRF52840 BLE Dev Board

This board is available for purchase [here](https://www.smart-prototyping.com/Zio-Qwiic-nrf52840-Dev-Board)

![nRF52840 Board](/nrf52840.JPG)

This is a development and breakout board based on nRF52840 SoC - a powerful combination of ARM Cortex-M4 CPU and 2.4GHz Bluetooth radio. With the nRF52840 at the heart of your project, you’ll be presented with a seemingly endless list of project-possibilities in an incredibly small package.


This board breaks out most of the nRF52840 module’s pins, including GPIO, UART, SPI, I2C, NFC, etc.. With the Micro USB connector, you can easily program and supply power to it. We’ve flashed [Adafruit’s nrf52 bootloader](https://github.com/adafruit/Adafruit_nRF52_Bootloader), an Arduino core for our nRF board, so you can interface with the arduino IDE. 


Additionally, we put a Qwiic connector on the board, so you can easily use our Qwiic modules with this development board. And there is a [full-color addressable LED WS2812-2020](https://www.smart-prototyping.com/WS2812-2020-Addressable-Fullcolor-RGB-LED) connected to Pin8. We also break out the NFC pins for NFC testing purpose. 

It also support programming with CircuitPython, check sparkfun’s tutorial [here](https://learn.sparkfun.com/tutorials/sparkfun-pro-nrf52840-mini-hookup-guide). 

You can find most of the technical specifications details from the [nRF52840 module datasheet](https://github.com/ZIOCC/Zio-nRF52840-BLE-Dev-Board/blob/master/MDBT50Q-P.pdf). 

**Other Specifications**

* Dimension: 57.4 x 23.9mm
* Weight: 5.1g
* Operation Voltage: 3.3V


**Links**

* [PCB schematic](https://github.com/ZIOCC/Zio-nRF52840-BLE-Dev-Board/blob/master/zio%20nRF52840%20BLE%20Dev%20Board.pdf)
* [PCB Source File](https://github.com/ZIOCC/Zio-nRF52840-BLE-Dev-Board/tree/master/EAGLE)
* [Datasheet](https://github.com/ZIOCC/Zio-nRF52840-BLE-Dev-Board/blob/master/MDBT50Q-P.pdf) 
* [Nordic nRF5 SDK](https://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF5-SDK) 
* [Bootloader Source Code](https://github.com/adafruit/Adafruit_nRF52_Bootloader)
* [Adafruit Arduino IDE tutorial](https://learn.adafruit.com/introducing-the-adafruit-nrf52840-feather)
* [Sparkfun CircuitPython tutorial](https://learn.sparkfun.com/tutorials/sparkfun-pro-nrf52840-mini-hookup-guide)
* [Pins definition](https://www.smart-prototyping.com/image/data/NOA-RnD/101968%20nrf52840%20dev%20board/nRF52840_variant.h)
* [GitHub](https://github.com/ZIOCC/Zio-nRF52840-BLE-Dev-Board)






###### About Zio
> Zio is a new line of open sourced, compact, and grid layout boards, fully integrated for Arduino and Qwiic ecosystem. Designed ideally for wearables, robotics, small-space limitations or other on the go projects. Check out other awesome Zio products [here](https://www.smart-prototyping.com/Zio).
