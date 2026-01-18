# Arduino LED Control Project

## Project Description

This project demonstrates how an Arduino can be controlled using a Python program through serial communication. The system allows LEDs connected to the Arduino to be turned ON or OFF by sending simple commands from a computer.

The project is composed of two main parts: an Arduino sketch that handles the hardware control, and a Python application that sends commands to the Arduino. The Python program uses FastAPI to provide a simple web-based interface for controlling the LEDs.

On the Arduino side, the board listens for incoming serial data. Each received command corresponds to a specific action, such as turning on a red, green, or blue LED, or turning all LEDs off.

On the Python side, a FastAPI server establishes a serial connection with the Arduino. When a user accesses an API endpoint, the program sends a single-character command to the Arduino through the serial port.

This project helps learners understand the basics of serial communication, Arduino hardware control, and how software applications can interact with embedded systems in real time.

