# Water Level Monitoring System

The Water Level Monitoring System is a project that utilizes an ESP32 microcontroller, an ultrasonic sensor, and web technologies to provide real-time updates of the water level in a tank. The system measures the water level using an ultrasonic sensor and displays the data on an HTML page, which can be accessed through a phone or any web-enabled device. This enables users to conveniently monitor the water level remotely and take appropriate actions if needed.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Hardware Requirements](#hardware-requirements)
4. [Software Requirements](#software-requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

The Water Level Monitoring System provides an efficient way to monitor the water level in a tank. It utilizes an ESP32 microcontroller, an ultrasonic sensor, and web technologies to offer real-time updates accessible through a web page. By measuring the water level using the ultrasonic sensor, the system accurately determines the current water level in the tank. The data is then displayed on an HTML page, which can be accessed through a phone or any web-enabled device, providing users with convenient remote monitoring capabilities.

## Features

- Real-time monitoring of the water level in a tank.
- Accurate measurement of the water level using an ultrasonic sensor.
- Web-based interface accessible through a phone or any web-enabled device.
- User-friendly HTML page displaying the water level data.
- Customizable thresholds for low and high water level alerts.
- Integration with the ESP32 microcontroller for data processing and web server functionality.

## Hardware Requirements

To build the Water Level Monitoring System, you will need the following components:

- ESP32 development board (e.g., ESP32 NodeMCU)
- Ultrasonic sensor (e.g., HC-SR04)
- Jumper wires
- Power supply
- Tank or container for water storage

## Software Requirements

The following software tools are required for setting up the project:

- Arduino IDE (Integrated Development Environment)

## Installation

1. Connect the components according to the circuit diagram provided.
2. Install the Arduino IDE by following the official instructions for your operating system.
3. Clone or download the project code from the repository.
   - If using Git, run the following command:
     ```
     git clone <repository-url>
     ```
   - Alternatively, download the code as a ZIP file and extract it to a local directory.

## Usage

1. Open the Arduino IDE and navigate to the project folder.
2. Open the `Water_Level_Monitoring_System.ino` file.
3. Set up the Wi-Fi credentials and modify any other necessary settings in the code.
4. Verify and upload the sketch to the ESP32 board.
5. Connect the ultrasonic sensor to the appropriate pins on the ESP32 board.
6. Power on the system and wait for the Wi-Fi connection to establish.
7. Access the HTML page by entering the IP address of the ESP32 in a web browser on your phone or any web-enabled device.
8. Monitor the water level displayed on the HTML page and take appropriate actions if needed.

## Contributing

Contributions to this project are welcome! If you find any issues or have ideas for improvements, please submit an issue or a pull request in the project's repository.

## License

The Water Level Monitoring System is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the `LICENSE` file for more information.
