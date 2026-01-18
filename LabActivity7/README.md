# Activity 7

This activity demonstrates how an Arduino can be controlled through a **web-based API** using Python and serial communication. A FastAPI application is used as a bridge between a web client and the Arduino, allowing LED control through HTTP requests.

On the Arduino side, LEDs are connected to designated digital pins and managed using commands received through the serial port. A separate header file is used to define pin assignments and constants, helping organize the code and improve readability. The Arduino listens for numeric serial commands and turns individual LEDs ON or OFF based on the received value.

On the computer side, a Python program built with **FastAPI** establishes a serial connection with the Arduino during server startup. The API exposes multiple endpoints that allow users to control the LEDs using a web browser or API client. Requests such as turning on a specific LED color, turning all LEDs on, or turning all LEDs off are translated into serial commands and sent to the Arduino.

The Python application handles API routing, input validation, serial communication, and safe startup and shutdown of the Arduino connection. Meanwhile, the Arduino focuses solely on hardware control and command execution.

This activity helps learners understand how embedded systems can be integrated with web technologies, how APIs can be used to control hardware remotely, and how serial communication enables interaction between microcontrollers and modern software applications.
