Water Dispenser Project

Project Name: Smart Water Dispenser
Author: RK Technologies
Description: This project is an IoT-based smart water dispenser that utilizes Arduino for automation. It measures water levels and dispenses a specific amount of water based on proximity detection, creating a convenient and touchless water dispensing experience.

Features

Automatic Water Dispensing: Detects when a container is placed within range and dispenses water accordingly.

Water Level Monitoring: Uses an ultrasonic sensor to ensure water availability.

Configurable Dispensing Volume: Easily adjust the amount of water dispensed by modifying a parameter in the code.

Energy Efficient: The system activates only when necessary, conserving power.


Components Used

Arduino UNO – Microcontroller to control the entire system.

Ultrasonic Sensor – Detects proximity to initiate water dispensing.

Servo Motor – Controls the water dispensing mechanism.


Getting Started

Prerequisites

Arduino IDE (for uploading code)

Basic knowledge of Arduino and electronics


Installation

1. Clone the repository:

git clone https://github.com/sankalp satpute/Water-Dispensers-Project.git


2. Upload the Code
Open the Arduino IDE, load the project code, and upload it to your Arduino UNO.


3. Circuit Setup
Connect the ultrasonic sensor and servo motor to the Arduino UNO as specified in the schematic.


Usage

1. Place a container under the sensor.


2. The sensor detects the object and activates the servo motor to dispense water.


3. Adjust the water dispensing time in the code if needed.



Code Explanation

main.ino: The main code file, which includes setup, proximity detection, and water dispensing functions.


Future Enhancements

Add a Wi-Fi or Bluetooth module for remote control and monitoring.

Integrate a display to show the current water level.

Implement a mobile app for tracking water usage.


License

This project is licensed under the MIT License.
