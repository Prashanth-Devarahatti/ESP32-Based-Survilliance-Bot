

# ESP32-CAM Robot

This project utilizes an ESP32-CAM module to create a remote-controlled robot with a live video feed. The robot can be controlled via a web interface hosted by the ESP32-CAM.

## Features

- **Remote Control:** Control the movement of the robot (forward, backward, left, right) via a web interface.
- **Live Video Stream:** Stream live video from the ESP32-CAM module to the web interface.
- **Simple Interface:** User-friendly interface with buttons for easy control.

## Hardware Requirements

- ESP32-CAM module
- Motor driver module
- DC motors (2)
- Chassis for the robot
- Power source (e.g., batteries)

## Software Requirements

- Arduino IDE
- ESP32 board support package
- ESP32-CAM library

## Installation

1. Clone this maincode to your local machine:

2. Open the project in the Arduino IDE.

3. Configure the project settings, including Wi-Fi credentials and camera model.

4. Upload the sketch to your ESP32-CAM module.

5. Connect the hardware components as per the wiring diagram.

6. Power on the robot and connect to its Wi-Fi network.

7. Open a web browser and navigate to the IP address of the ESP32-CAM to control the robot.

## Wiring Diagram

![Wiring Diagram](wiring_diagram.png)

## Usage

1. Connect to the Wi-Fi network hosted by the ESP32-CAM.

2. Open a web browser and enter the IP address of the ESP32-CAM.

3. Use the provided buttons on the web interface to control the robot's movement.




