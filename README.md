# Project Tesla
Project Tesla is a DC-to-DC conversion project designed and developed in 0.18um high voltage CMOS SOI process. This project uses a programmable bandgap reference (BGR) circiit, a R-2R ladder digital-to-analog converter (DAC) circuit, a serial Peripheral interface (SPI) circuit and a ring voltage contorled oscillator (VCO) circuit.
# Bandgap Voltage Reference (BGR)
A bandgap voltage reference is a temperature independent voltage reference circuit widely used in integrated circuits. It produces a fixed (constant) voltage regardless of power supply variations, temperature changes and circuit loading from a device. It commonly has an output voltage around 1.2 V (close to the theoretical 1.205 eV band gap of silicon at 0 K).
## Parameters
- **Output Voltage (VO) (V)**:
- **Initial Accuracy (Max) (%)**:
- **Temp Coeff (Max) (ppm/ degree C)**:
- **Input Voltage (Min/Max) (V)**:
- **Quiescent Current (IQ) (uA)**:	
- **Iout/Iz (Max) (mA)**:
- **Operating Temperature Range (C)**:

## Features
## Applications
## Description
An op-amp based bandgap reference is designed. The small size and low power consumption of the BGR make it ideal for portable and battery-powered applications. This BGR can be operated from a supply of as low as 1.5V to the maximum supply voltage of 5V. This BGR provides a temperature coefficient (tempco) less than 20 ppm/degree-centigrade for a wide range of temperature sweep (–40°C to +125°C). Fig. 1 shows the circuit diagram of BGR. The BGR consists a core circuit, a opreational amplifier, a start-up circuit and a ztat circuit. Here the main function of the operational amplifier is to equal the voltages at two input nodes and also equals the currents through two branches. The start-up circuit makes the BGR operational during the turn-on of power. The ztat circuit is additiobally connected to the BGR to generate the very low tempco currents or currents almost independent of temperature. More detail description of above circuits is provided in their idividual sections.

### Op-amp Circuit
### Start-up Circuit
### ZTAT Circuit

# Serial Peripheral Interface (SPI)
The Serial Peripheral Interface (SPI) is a synchronous serial communication interface specification used for short-distance communication, primarily in embedded systems.
# R-2R Ladder Digital-to-Analog converter (DAC)

# Ring Voltage Controlled Oscillator (VCO)
