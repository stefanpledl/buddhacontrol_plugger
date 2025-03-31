# Build Your Own Plugger - The Smart Cannabis Storage & Drying Controller

[![License: CC BY-NC 4.0](https://licensebuttons.net/l/by-nc/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc/4.0/)

## What is Plugger?

Plugger is a smart controller device by BuddhaControl that transforms your regular refrigerator into a precision cannabis storage and drying system. By maintaining optimal temperature and humidity conditions, Plugger ensures your cannabis stays fresh, properly cured, and at peak quality.

## How It Works

Plugger connects to your refrigerator via a smart plug and uses sensors to monitor the environment. The controller automatically manages the refrigerator's operation to maintain ideal conditions for cannabis storage and drying. No modifications to your refrigerator are needed - just Plugger, a smart plug, and your existing fridge.

## Build Your Own Plugger

This repository contains the open-source firmware for DIY enthusiasts who want to build their own Plugger device. Currently, firmware is available for:

1. **Plugger Pro** - With display for easy monitoring and control (uses ESP32 CYD)
2. **Plugger Mini** - *(Coming soon)* Without display for discreet, space-saving installation

## Required Hardware

### For Plugger Pro:
- ESP32 CYD (ESP32 with integrated display)
- SHT40 temperature and humidity sensor
- Smart plug (WiFi-enabled)
- Power supply
- Enclosure

### For Plugger Mini:
- ESP32-C3 microcontroller
- SHT40 temperature and humidity sensor
- Smart plug (WiFi-enabled)
- Power supply
- Enclosure

## SHT40 Sensor Connection

The SHT40 temperature and humidity sensor connects to the ESP32 as follows:

For Plugger Pro (ESP32 CYD) connect to JSP connector CN1:
- GND: Black wire
- 3V: Red wire
- IO22: Yellow wire (SDA)
- IO27: White wire (SCL)

## Installation

1. Download the latest firmware release from the [Releases](https://github.com/buddhacontrol/plugger/releases) page
   - Currently, only Plugger Pro firmware is available
2. Flash the firmware to your ESP32 using PlatformIO or Arduino IDE
3. Connect the SHT40 sensor as described above
4. Power up your device and follow the setup instructions

## Setup and Configuration

To set up and configure your Plugger device:

1. Download the BuddhaControl app from [buddhacontrol.com/download](https://buddhacontrol.com/download)
2. Install the app on your smartphone or tablet
3. Power on your Plugger device
4. Open the app and follow the on-screen instructions to connect to and configure your device

## Features

- Precise temperature and humidity control
- Smart drying cycles for optimal curing
- Long-term storage mode
- WiFi connectivity for remote monitoring
- Mobile app compatibility
- Customizable settings

## License

This project is released under a [Non-Commercial License](LICENSE). You are free to build and modify Plugger for personal use, but commercial use or sale of devices using this firmware is prohibited without explicit permission from BuddhaControl.

## Official Version

For those who prefer a ready-to-use solution, the official Plugger device is available for purchase at [BuddhaControl.com](https://buddhacontrol.com).

## Support

For questions about building your own Plugger, please open an issue in this repository.

For support with official Plugger products, please contact BuddhaControl customer service.
