# Moledcule Plate

This repository contains the design and firmware for the Moledcule Plate, a WS2812B Universal Restrictor Plate for Fightstick Joysticks. The plate is designed to enhance the visual experience of fightsticks by integrating programmable LED lighting.

![Restrictor Plate](https://github.com/moledcule/plate/blob/master/plate.png)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Moledcule Plate is a printed circuit board (PCB) designed to fit into fightstick joysticks. It includes WS2812B LEDs arranged in a circular pattern, providing customizable lighting effects. This plate adds a visual flair to your fightstick, making it stand out in both casual and competitive settings.

## Features

- Compatible with most fightstick joysticks
- 8 WS2812B LEDs for vibrant lighting effects
- Easy installation and setup
- Customizable through firmware updates
- Low power consumption

## Requirements

- Moledcule Plate PCB
- Fightstick joystick compatible with the plate
- Power source (typically 5V via USB)
- Microcontroller (e.g., Arduino, ESP8266, ESP32) for controlling the LEDs
- Required libraries and dependencies for the microcontroller

## Installation

1. **Hardware Setup:**
   - Install the Moledcule Plate into your fightstick joystick.
   - Connect the plate to a power source.
   - Connect the data line of the WS2812B LEDs to the microcontroller.

2. **Software Setup:**
   - Clone the repository:

     ```bash
     git clone https://github.com/moledcule/plate.git
     cd plate
     ```

   - Install the necessary libraries for your microcontroller. For example, if using an Arduino:

     ```bash
     arduino-cli lib install "Adafruit NeoPixel"
     ```

   - Upload the provided firmware to your microcontroller.

## Usage

1. Power on your fightstick with the Moledcule Plate installed.
2. The LEDs should light up according to the default configuration.
3. Customize the lighting effects by modifying the firmware and re-uploading it to the microcontroller.

## Contributing

We welcome contributions to the Moledcule Plate project. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Create a pull request to the main repository.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
