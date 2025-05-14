# Adafruit_INA237_INA238
Arduino library for the INA237 and INA238 power monitors

[![Build Status](https://github.com/adafruit/Adafruit_INA237_INA238/workflows/Arduino%20Library%20CI/badge.svg)](https://github.com/adafruit/Adafruit_INA237_INA238/actions)
[![Documentation](https://raw.githubusercontent.com/adafruit/ci-arduino/master/assets/doxygen_badge.svg)](https://adafruit.github.io/Adafruit_INA237_INA238/html/index.html)

This is the Adafruit INA237 and INA238 Current and Power sensor library.

## Device Information

The INA237 and INA238 are functionally identical devices with different part numbers. They share:
- Same register map
- Same device ID (0x238)
- Same measurement capabilities and accuracy
- Same configuration options

This library provides separate classes for each part number for clarity:
- `Adafruit_INA237` - For INA237 devices
- `Adafruit_INA238` - For INA238 devices (a thin wrapper around the INA237 implementation)

Tested and works great with the Adafruit INA237 and INA238 Breakout Boards.

These chips use I2C to communicate, 2 pins are required to interface.

## Installation

To install, use the Arduino Library Manager and search for "Adafruit INA237" and install the library.

## License Information

Adafruit invests time and resources providing this open source code,
please support Adafruit and open-source hardware by purchasing
products from Adafruit!

Written by Limor "Ladyada" Fried for Adafruit Industries.
MIT license, check license.txt for more information
All text above must be included in any redistribution
