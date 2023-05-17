# ArduCAM Library Introduction
This is a opensource library for taking high resolution still images and short video clip on Arduino based platforms using ArduCAM's camera moduels.
The camera breakout boards should work with ArduCAM shield before connecting to the Arduino boards.
ArduCAM mini series camera modules like Mini-2MP, Mini-5MP(Plus) can be connected to Arduino boards directly.
In addition to Arduino, the library can be ported to any hardware platforms as long as they have I2C and SPI interface based on this ArduCAM library.

## Now Supported Cameras
* OV7660 0.3MP  
* OV7670 0.3MP  
* OV7675 0.3MP  
* OV7725 0.3MP  
* MT9V111 0.3MP  
* MT9M112 1.3MP  
* MT9M001 1.3MP  
* MT9D111 2MP  
* OV2640 2MP JPEG  
* MT9T112 3MP  
* OV3640 3MP  
* OV5642 5MP JPEG  
* OV5640 5MP JPEG  
##  Supported MCU Platform  
* Theoretically support all Arduino families  
* Arduino UNO R3 (Tested)
* Arduino MEGA2560 R3 (Tested)
* Arduino Leonardo R3 (Tested)
* Arduino Nano (Tested)
* Arduino DUE (Tested)
* Arduino Genuion 101 (Tested)
* Raspberry Pi (Tested)
* ESP8266-12 (Tested) (http://www.arducam.com/downloads/ESP8266_UNO/package_ArduCAM_index.json)
* Feather M0 (Tested with OV5642)
> Note: ArduCAM library for ESP8266 is maintained in another repository ESP8266 using a json board manager script.
