# Rubik-s-cube-solver-using-Arduino-UNO

##Video link: https://www.youtube.com/watch?v=UytTCMy3AUE

This project is an Arduino-based Rubik's Cube solver that uses servos to manipulate the cube. It receives the cube's current state and a solution string via serial communication and then moves the cube accordingly to solve it.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)

## Requirements

- Arduino board (tested with Arduino Uno)
- 2 Servo motors
- Custom Rubik's Cube holder compatible with servos
- Serial communication setup for sending the cube's state and solution string

## Installation

1. Clone this repository or copy the provided Arduino code.
2. Connect the servos to the appropriate pins on the Arduino board (pin 6 for the arm servo and pin 5 for the Rubik's Cube servo).
3. Attach the servos to the custom Rubik's Cube holder.
4. Upload the code to your Arduino board.

## Usage

1. Ensure the serial communication setup is properly configured to send the cube's state and solution string to the Arduino.
2. Power on the Arduino and wait for the "Arduino is ready" message to appear in the serial monitor.
3. Place the scrambled Rubik's Cube in the holder.
4. Send the cube's state and solution string via serial communication.
5. The Arduino will move the servos according to the solution string, solving the Rubik's Cube.

## Acknowledgements

This project is based on the Arduino platform and uses servo motors for moving the Rubik's Cube. It also relies on external algorithms and software for generating the solution string based on the cube's current state.
