Activity 2 – Working with Analog Signals (LED Brightness Control)

This activity builds on the first running light project and introduces the use of analog signals to control LED brightness. Instead of simply turning LEDs ON or OFF, this activity uses Pulse Width Modulation (PWM) to vary the brightness of each LED.

The circuit still uses five LEDs connected to Arduino pins 8 to 12. The running light follows the same pattern as the first activity: LEDs turn ON one by one from pin 12 down to pin 8, then turn OFF one by one in the same order, with a one-second delay between each step. However, brightness control is now handled using `analogWrite()`.

An array is used to store the LED pin numbers, making the code more organized and easier to manage. A `while()` loop is implemented to iterate through the array and control the LEDs instead of using multiple individual statements. This approach demonstrates a more structured way of handling multiple output pins in Arduino programming.

During execution, the program gradually activates each LED at a specified brightness level using `analogWrite()`, pauses for one second, and then proceeds to the next LED. After all LEDs have been activated, the program turns them off sequentially using the same loop logic.

This activity helps learners understand analog signal simulation in Arduino, the use of PWM for brightness control, and how arrays and `while()` loops can simplify and improve code structure.
