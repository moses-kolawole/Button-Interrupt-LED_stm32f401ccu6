# Binary_Counter_LEDs_STM32F401CCU6

## Overview

A bare-metal STM32 project demonstrating a 4-bit binary counter using four LEDs on the STM32F401CCU6 Black Pill board.

## Project Codes
[Click Here to check out the project code](code)

## Project images
![Click here to access the project images](images/IMG_20260722_181624_649.jpg)

## Hardware

* STM32F401CCU6 Black Pill
* 4 LEDs
* 4 × 220Ω Resistors
* ST-Link V2
* STM32CubeIDE

## Features

* GPIO Output Configuration
* Bit Manipulation
* Binary Number Representation
* Multi-LED Control
* Bare-Metal Programming (No HAL)

## Program Flow

```text id="l5n4q1"
0000
 ↓
0001
 ↓
0010
 ↓
0011
 ↓
...
 ↓
1111
 ↓
Repeat
```

## Expected Output

The four LEDs count in binary from **0 to 15**, continuously repeating the sequence.

Example:

```text id="pk2ef2"
Decimal    Binary
0          0000
1          0001
2          0010
3          0011
...
15         1111
```

## Project Demo video
[Click Here to check out the project demonstration Video](https://youtu.be/W-dG8b2Q2J8)

