# Open source avionics lights system for experimental aircrafts
 This project consists of a pure hardware avionics lights system that includes both hardware list of components and diagram to build DIY on your own risk.
 
# Info
 This repository contains all the hardware and software files for an open source avionics lights system.
 The system includes navigation, landing, strobe, and taxi lights for aircraft.
 The system is based on pure hardware, using a 555 timer chip, and does not require any code.

# Hardware
 The hardware consists of a circuit board that connects the 555 timer chip with a series of resistors, switches, and LEDs.
 The circuit diagram and schematic are provided in the `hardware` folder.
 The circuit can be powered by a 12V battery.

# Software
 No software is needed, but if you want to modify the logic and timing of the lights, you can connect an Arduino or a Raspberry Pi board.
 
# Here are some steps to follow:
 ## Step 1: Determine the types of lights needed, such as navigation, landing, strobe, and taxi lights, and consider their size, shape, color, brightness, and power consumption.
 - using all in this project, with some extras like, landing light triple switch for blink left then right, Allways Both On, OFf

 ## Step 2: Design a hardware circuit to control the lights. Use pure hardware or microcontrolers to program the logic and timing of the lights, and choose appropriate sensors, switches, resistors, capacitors, LEDs, and wires for your circuit.
 - pure hardware, will be safer and more smart on energy consumption.

 ## Step 3: Test and debug your circuit to ensure it works as expected. The hardware should read inputs from sensors and switches, and send outputs to the LEDs.
 - Tested, 2 weeks 24h non stop. All seems good. But use at your own risk. 

# List of hardware components:
- Voltage regulators: 5V, 10V, adjustable
- 2x NE555 Timer (Can be one only, First controls each LED on/off, second blinks the LED faster)
- 1x CD4017 CMOS-Decade counter/divider
- Transistors: NPN and PNP
- Capacitors: electrolytic
- Resistors: fixed (330 ohms) for LEDs (may not be necessary if you use an output of under 10V for LEDs)
- Resistors: adjustable (100k ohms)

## LEDs: 12V - 10W
- 4x 10W White LEDs (2x Landing Right and 2x Landing Left - wings)
- 3x 10W White LEDs (Left, Right, Tail)
- 2x 10W Red LEDs (Right, Taxi)
- 1x 10W Green LED (Left)
- Switches:
- Physical switches to turn on and off
- 3-button switch for landing light: Off, always ON, Blink left then right


# Usage
 To use the system, you need to connect the circuit board to a 12V battery and mount the LEDs on your aircraft.
 You can use the switches to turn on and off the different types of lights.
 You can also use the resistors on the input voltage regulators to adjust the brightness of the lights.

# License
 This project is licensed under the CopyLeftToAnotherPlanet. See the `LICENSE` file for more details.
