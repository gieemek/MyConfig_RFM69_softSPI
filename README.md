MyConfig for MySensors library working with RFM69 radio module via software SPI
===============================================================================

This is configuration file for MySensors library for use with RFM69 radio module with software SPI implemented.

Just download it and put to your MySensors library folder.

I only changed the number of MY_ATSHA204_PIN from 17 to 18, because I use 17 pin to software SPI communication. If you will not use 17 pin for SPI, you don't need to get this file.

To use MySensors library with RFM69 module via software SPI, you need to download RFM69_softSPI library from my another repository.

In the MQTTGateway repository you can find Arduino sketch to build MQTT Broker Gateway with RFM69 module using software SPI (modified MySensors MQTTGateway.ino sketch).