# Midterm Exam – Internet of Things

This project implements a smart lighting system using Arduino. A light sensor is used to measure ambient light intensity, and the readings are converted into percentage values. Based on the measured light level, the system controls three LEDs to represent different lighting conditions, with only one LED active at a time.

The system supports both manual and automatic modes. In manual mode, the user can send commands through serial communication to control the system. In automatic mode, the Arduino adjusts the LED behavior based on predefined light intensity thresholds to simulate cloudy, normal, and bright environments.

Serial communication is used to display the current light intensity, system mode, and environment status, as well as to receive user commands from an external program such as a Python script. This project demonstrates basic sensor integration, automation logic, and real-time communication between hardware and software.
