# Open source avionics lights system for experimental aircrafts
All avionics lights system hardware and software - Navigation, landing, strobe and taxi

This project consists on pure hardware, no code where it makes use of the 

an open source avionics lights system that includes both hardware and software components, here are some steps you can follow:

- There are different types of lights, such as navigation, landing, strobe, taxi, etc. You also need to consider the size, shape, color, brightness, and power consumption of the lights.
- Design hardware circuit that will control the lights. You can use a microcontroller, such as Arduino or Raspberry Pi, to program the logic and timing of the lights. You also need to choose the appropriate sensors, switches, resistors, capacitors, LEDs, and wires for your circuit.
- Hardware reads inputs from the sensors and switches, and send the outputs to the LEDs. You also need to test and debug your code to make sure it works as expected.

# Info

This repository contains all the hardware and software files for an open source avionics lights system. The system includes navigation, landing, strobe, and taxi lights for aircraft. The system is based on pure hardware, using a 555 timer chip, and does not require any code.

## Hardware

The hardware consists of a circuit board that connects the 555 timer chip with series of resitors,  switches, and the LEDs. The circuit diagram and the schematic are provided in the `hardware` folder. The circuit can be powered by a 12V battery.

## Software

No software is needed but if you want to modify the logic and timing of the lights. You can connect to Arduino or a Raspberry Pi board. 

## Usage

To use the system, you need to connect the circuit board to the 12v battery, and mount the LEDs on your aircraft. You can use the switches to turn on and off the different types of lights. You can also use the resitors on the input voltage regulators to adjust the brightness of the lights.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
