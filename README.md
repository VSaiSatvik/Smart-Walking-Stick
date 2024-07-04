# Smart-Walking-Stick
This project integrates a step counter and an obstacle detection system into a walking stick, enhancing mobility for users who need assistance. Utilizing an MPU6050 accelerometer and gyroscope sensor, along with IR sensors and a passive buzzer, the system tracks the number of steps taken and alerts the user to obstacles in their path.

Components

Arduino Board: The microcontroller to run the code.
MPU6050: Accelerometer and gyroscope sensor to detect motion and count steps.
IR Sensors: Two infrared sensors to detect obstacles.
Passive Buzzer: Provides audible alerts for obstacle detection.
Breadboard and Jumper Wires: For connecting the components.
Features

Step Counting: Counts the number of steps taken by the user and displays the count on the serial monitor.
Obstacle Detection: Detects obstacles using IR sensors and alerts the user with a buzzer sound.
Real-Time Monitoring: Continuously monitors and updates the step count and obstacle status.
Usage

Setup: Connect the components as described in the circuit diagram. Ensure the MPU6050 is calibrated and properly connected to the Arduino.
Upload Code: Upload the provided Arduino code to the Arduino board.
Monitor Steps and Obstacles: Open the serial monitor to view the step count and receive alerts when an obstacle is detected.
Circuit Diagram

MPU6050:
VCC to 3.3V or 5V on Arduino
GND to GND on Arduino
SCL to A5 on Arduino
SDA to A4 on Arduino
IR Sensors:
VCC to 5V on Arduino
GND to GND on Arduino
OUT1 to digital pin 8 on Arduino
OUT2 to digital pin 7 on Arduino
Passive Buzzer:
VCC to 5V on Arduino
GND to GND on Arduino
Signal pin to digital pin 9 on Arduino
