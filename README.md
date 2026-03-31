# Flexible For Arduino

[Flexible For Arduino](https://plugins.jetbrains.com/plugin/31027-flexible-for-arduino) is a plugin for JetBrains IDEs that brings full embedded development for ESP32, Arduino, STM32, nRF52, and RP2040 boards — build, flash, debug, and monitor without leaving your IDE.

This repository exists as a community hub and issue tracker.

## Feedback and Support

If you have any feedback, suggestions, or issues with the plugin, please use this GitHub repository to report them. You can also use the repository to request new features or share ideas.

- GitHub repository: [Flexible For Arduino](https://github.com/ilscipio/flexible-arduino-jetbrains-plugin)
- Ilscipio Agency: [Ilscipio](https://www.ilscipio.com/en)
- AI Project: [Aivory](https://aivory.net)
- Email: info@ilscipio.com

## Features

- **Build, Flash & Monitor** — ESP-IDF, Arduino CLI, PlatformIO, and Zephyr backends with a single run configuration
- **Serial Monitor** — COM port auto-detection, configurable baud rate, send commands, DTR/RTS control, auto-reconnect
- **Language Intelligence** — Syntax highlighting, code completion, hover docs, structure view, and formatting for Arduino C++
- **Pin Viewer & Sketch Pin Mapper** — Interactive chip diagram, pin capabilities table, detect and reassign pin assignments in your sketch
- **JTAG Debugging** — GDB/OpenOCD integration with breakpoints and watch expressions (Pro)
- **OTA Upload** — Over-the-air firmware updates (Pro)
- **Memory Analyzer** — Visualize RAM and Flash usage per section and component (Pro)
- **Device Profiler** — Runtime performance profiling streamed from the device (Pro)
- **sdkconfig Editor** — Search, category grouping, and inline editing for ESP-IDF configuration
- **Blockly Editor** — Drag-and-drop visual programming that generates Arduino C++ code
- **MCP AI Server** — Built-in Model Context Protocol server for AI-assisted embedded development
- **20+ board definitions** — ESP32 family (S2/S3/C3/C6/H2/P4), ESP8266, Arduino Uno/Nano/Mega/Leonardo, RP2040 Pico, nRF52840, STM32 Nucleo/Blue Pill/Black Pill

## Installation

You can install Flexible For Arduino from the JetBrains Marketplace or from the IDE settings.

- **From the Marketplace**: Go to [Flexible For Arduino](https://plugins.jetbrains.com/plugin/31027-flexible-for-arduino) and click the Install button. Then restart your IDE.
- **From the IDE**: Go to File > Settings > Plugins and search for "Flexible For Arduino". Click Install and restart.

## Getting Started

1. Install the plugin from JetBrains Marketplace
2. Open or create an ESP32/Arduino project (`.ino` sketch or ESP-IDF `CMakeLists.txt`)
3. Configure the SDK path at **Settings > Languages & Frameworks > Arduino/ESP-IDF**
4. Select your board and COM port in the **Arduino tool window** at the bottom
5. Hit **Build**, **Flash**, or **Build & Flash** from the toolbar or the Tools > Arduino menu

## Requirements

- **JetBrains IDE** 2023.3 or later (IntelliJ IDEA Community/Ultimate, CLion, PyCharm, etc.)
- **ESP-IDF v4.x or v5.x** (for ESP32 development) or **Arduino CLI** (for Arduino boards)
- **USB driver** for your board's USB-to-serial chip (CP2102, CH340, FTDI, etc.)
