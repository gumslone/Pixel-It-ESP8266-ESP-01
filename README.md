# Pixel It
Pixel It, WS2812b 8x32 Led Matrix Display Software for ESP8266 ESP-01 Module

ESP8266 ESP-01 Version of Pixel IT

Removed MP3, LDR and DHT Libraries, changed the PIN to gpio2 so it works with ESP-01 Module.

Just flash the .bin file to your ESP-01 Module, connect the GPIO2 pin to Data Pin of the Matrix and you are good to go.

Button should be connected between GPIO0 and GND, to read the button presses via MQTT use: /pixelit/Button.

15 seconds long buttonpress will do a factory reset.

5 short button presses within 2 seconds will restart the ESP8266.

I recommend to use a ws2812b driver module for ESP-01.

The WS2812 Driver for ESP-01 that im using is available at Tindie https://www.tindie.com/products/21371/ , but other ESP-01 Based drivers will work too.
