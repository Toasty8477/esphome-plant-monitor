# ESPHome Plant Monitor

## What is this?
A soil moisture monitor for your plants. It's built using ESPHome running on an ESP32 C3, a few capacitive soil moisture sensors, and an ssd1306 display.

## Why is this?
I wanted a better way to keep track of when to water my plants because I always forget. Using Home Assistant I set up notifications so that if a plant gets too low on water a notification is sent to my phone. I didn't want to spend a ton of money on custom pcbs or a ton of time figuring out how to jam components into a reasonably sized case so all the sensors are routed back to a single device. 

## What's inculded
Currently just a .yaml file with the config but in the future there will be more.

## Planned features
- Better documentation
- Support for notifications without needing to use home assistant
- A more modular design for the config
- Ambient light sensor support
- Temperature sensor support