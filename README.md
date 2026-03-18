# mixer-motor-controller
220V 2000W mixer motor speed control project
# Mixer Motor Speed Controller

## Description
This project controls the operation time of a 220V 2000W mixer motor using an STM32 microcontroller.
## Features
Timer based motor control
Two preset operating times (7 min and 15 min)
Start / Stop toggle control
Implemented using STM32 HAL library
- Designed for AC motor load
- Simulation done in Proteus
  ## Operation
Button PB0 : runs the mixer for 7 minutes  
Button PB1 : runs the mixer for 15 minutes  
Button PB10 : start / stop toggle  

Output pin PA0 drives the motor control circuit.

## Hardware
- Triac driver circuit
- Power control stage
## Microcontroller
STM32 microcontroller using HAL library
## Software
- Embedded C
