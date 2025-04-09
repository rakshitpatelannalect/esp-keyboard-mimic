# ESP Keyboard Mimic

A hardware-software solution for automatic keyboard input using ESP32 microcontroller.

## Problem Statement

Many secure systems prevent copy-pasting of sensitive information like passwords or banking details, forcing users to manually type this information. This project provides a secure alternative by emulating physical keyboard input.

## Features

- ESP32-based USB HID keyboard emulation
- Floating window application for text capture
- Bluetooth connectivity for device communication
- Physical stop button for immediate interruption
- Secure text transmission from application to ESP device
- Exclusive Bluetooth device pairing for enhanced security

## Components

### Hardware
- ESP32 development board
- Optional custom PCB with physical controls
- USB connection to target device

### Software
- ESP32 firmware with USB HID implementation
- Cross-platform desktop application
- Web configuration portal

## Development Roadmap

1. **Phase 1:** ESP32 basic keyboard emulation and connectivity
2. **Phase 2:** Floating window application development
3. **Phase 3:** Web portal implementation
4. **Phase 4:** Security implementation
   - Bluetooth bonding with paired device only
   - Encryption of text during transmission
   - Device authentication mechanism
   - Secure erase functionality for sensitive data
   - Hardware button confirmation for security operations
5. **Phase 5:** Password/text manager functionality

## License
MIT License
