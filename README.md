# SONOFF PIR

Custom firmware for SONOFFs fitted with a PIR motion sensor.
The PIR motion sensor is connected to the exposed pin of SONOFF.


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

NOTE: newer SONOFFS require the flashing mode to be set to DOUT
