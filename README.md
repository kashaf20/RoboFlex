# RoboFlex Project 

Welcome to the RoboFlex project! This document will guide you through the setup, assembly, and operation of the robotic arm, pan-tilt servo assembly, and the associated vehicle assembly.

## Components

- **Robotic Arm Assembly**
- **Pan-Tilt Servo Assembly**
- **Car Assembly**

## Connections

### ESP32 Board
- [ESP32 Board URL](https://dl.espressif.com/dl/package_esp32_index.json)

### Required Libraries
- **AsyncTCP Library:** [Download from GitHub](https://github.com/me-no-dev/AsyncTCP/archive/refs/heads/master.zip)
- **ESPAsyncWebServer Library:** [Download from GitHub](https://github.com/me-no-dev/ESPAsyncWebServer/archive/refs/heads/master.zip)

## Code Upload

1. Install the **Arduino IDE** and ESP32 board support package.
2. Download and install the required libraries.
3. Connect the ESP32 to your PC via USB.
4. Open the provided **RoboFlex code** in Arduino IDE.
5. Select the correct ESP32 board and COM port.
6. Click **Upload** to flash the code onto the ESP32.

## Operation Instructions

### 1. Powering Up the System
- Connect the power supply to the robotic arm.
- Connect your mobile device to the ESP32 via Wi-Fi.

### 2. Accessing the Web Interface
- Open a compatible web browser on your mobile or computer.
- Type `192.168.4.1` in the browser’s address bar to access the control interface.

### 3. Controlling the Robotic Arm
- Use the web interface to select desired movements for each axis.
- Monitor real-time feedback to ensure accurate positioning.

### 4. Stopping Operations
- Power off the system when not in use.

## Code Explanation

The project utilizes **AsyncTCP** and **ESPAsyncWebServer** libraries for handling asynchronous TCP communication and managing a lightweight web server. The ESP32 serves as the central controller, receiving commands via a web interface and translating them into motor movements.

## Demo

Follow the steps below to see the RoboFlex project in action:

1. Power on the ESP32 board.
2. Connect to the ESP32’s Wi-Fi from your mobile app or browser.
3. Use the web interface to control the robotic arm, pan-tilt servos, and vehicle movements.
4. Monitor real-time data and explore different functionalities.

## Troubleshooting

### 1. Connectivity Issues
- Ensure that your mobile device is connected to the ESP32 via Wi-Fi.

### 2. Servo Malfunction
- Inspect the power supply to ensure adequate voltage.
- Test the affected servo motor individually.
- Replace faulty servo motors if necessary.

### 3. Web App Not Responding
- Refresh the web application.
- Ensure the ESP32 microcontroller is powered on and functioning.

## Important Points

- Ensure all components are **securely assembled** before operation.
- Keep the ESP32 **adequately powered** for stable performance.
- Regularly check for **firmware updates** and improvements.
- If experiencing issues, refer to **troubleshooting guides**.

Enjoy exploring the capabilities of **RoboFlex**!
