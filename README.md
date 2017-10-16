# SONOFF PIR
Custom firmware for SONOFF equipped with a PIR motion sensor


## Requirements
* Arduino IDE with [support for ESP8266](https://github.com/esp8266/Arduino)
* [Async MQTT client](https://github.com/marvinroger/async-mqtt-client)
* [ESPAsyncTCP](https://github.com/me-no-dev/ESPAsyncTCP)

## Arduino flashing settings

* Type of board: Generic ESP8266
* Flash Mode: DIO
* Flash Frequency: 40MHz
* CPU Frequency: 80MHz
* Flash Size: 1M (64K SPIFFS)
* Debug Port: Disabled
* Debug Level: None
* Reset Method: ck
* Upload Speed: 115200
