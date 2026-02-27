# Banff

## Overview
Electronic project "Banff" is an activity for a children summer camp.

This project is based on the `rgbfade.c` project by Kevin Mehall (2008). It is designed for the ATtiny13 microcontroller with an internal clock frequency of 1 MHz. The project includes functionality for controlling RGB LEDs and their fading states.

<img src="Doc/Banff lesson/DSC_2563.JPG">

This project is named after Banff National Park in Alberta, Canada.

## Components List (Digikey Part Number)
- ATtiny13 microcontroller (ATTINY13A-PU-ND)
- RGB LEDs (generic)
- Resistors (generic 300ohm)
- Push button (EG1829-ND)
- Breadboard (sparkfun part #?)
- Battery case (to be updated)
- Battery (to be updated to CR2032)

## Schematic
[to be added]

## Software Dependencies
- AVR GCC Toolchain
- AVR IO library
- AVR Sleep library
- AVR Interrupt library
- AVR Delay library

## Build Instructions
[to be updated to modern toolchain]
1. Navigate to the `Debug` or `Release` directory.
2. Use the provided `Makefile` to build the project. Run the following command:
   ```
   make
   ```

## Flashing Instructions
1. Use an AVR programmer "Dragon" (ATAVRDRAGON-ND) to flash the compiled `.hex` file to the ATtiny13 microcontroller.
2. Ensure the correct clock frequency (1 MHz) is set for the microcontroller.

## Usage
The project is used to control RGB LEDs with various fading states. The fading states include transitions between colors such as red, yellow, green, cyan, blue, and violet. The fading state can be changed by pressing the push button.

## Todo List
- [ ] Provide a detailed schematic for the project.
- [ ] Add specific component values for resistors and capacitors.
- [ ] Update the build toolchain to use modern tools
- [ ] Include detailed flashing instructions.
- [ ] Add usage examples and documentation.

## License
The project includes files with different licenses:
- Some files are released under the GNU/GPL License.
- Some files are licensed under a Creative Commons Attribution-NonCommercial 2.5 License.

Please review the individual files for specific licensing details.