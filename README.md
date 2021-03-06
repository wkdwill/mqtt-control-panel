# mqtt-control-panel

A simple alarm control panel for Home Assistant's `manual_mqtt` alarm. Designed to run on a Raspberry Pi using an Adafruit 3.5" PiTFT.

Video of the control panel in action: <https://www.youtube.com/watch?v=2Lei8n_aSJI>

Instructions for building your own: <https://www.hackster.io/colinodell/diy-alarm-control-panel-for-home-assistant-ac1813>

Display mockup:

![](screenshot.png)

# Hardware

 - Raspberry Pi Zero Wireless (other modern Pis will likely work fine)
 - [Adafruit PiTFT 3.5" display](https://www.adafruit.com/product/2441)

# Requirements

This project requires Python 2.7 with the following packages:

 - paho-mqtt
 - pygame
 - python-dotenv

**IMPORTANT:** SDL 2.x and SDL 1.2.15-10 have some serious incompatibilities with touchscreen. You can force SDL 1.2 by running a script: https://learn.adafruit.com/adafruit-pitft-28-inch-resistive-touchscreen-display-raspberry-pi/pitft-pygame-tips#ensure-you-are-running-sdl-1-dot-2

# Configuration

Copy `.env.dist` to `.env` and update the values accordingly.
