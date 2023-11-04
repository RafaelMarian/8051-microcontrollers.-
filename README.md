# 8051 Microcontrollers for Environmental Monitoring

## Overview

The primary objective of our project was to create a more efficient environment for plants and trees. The circuits developed were designed to collect environmental data and relay it to peripherals. This allowed us to measure the liquid level in the ground, enabling us to determine whether plants and trees required more or less water. For this purpose, an analog sensor SEN0114 was employed. The sensor is linked to an Analog-to-Digital Converter (ADC) which converts analog data into digital format before transmitting it to a microcontroller.

Another integral component of our setup was a digital sensor BMP180, requiring the use of the I2C protocol for data transmission and reception. This sensor was later integrated with the microcontroller to enhance data collection capabilities.

In the final stage, the collected data was displayed on an LCD screen. The code used for this project was written in Assembly language, and the programs utilized were Keil uVision 5 and Proteus.

## Components Used

- **Analog Sensor (SEN0114):** Measures the liquid level in the ground to determine the water requirements for plants and trees.
- **Analog-to-Digital Converter (ADC):** Converts analog data from the sensor into digital format for processing.
- **Digital Sensor (BMP180):** Utilizes I2C protocol for digital data transmission and reception.
- **Microcontroller (8051):** Receives and processes data from both sensors for environmental monitoring.
- **LCD Display:** Used to present the collected data for observation and analysis.

## Tools and Software

- **Programming Language:** Assembly language was used to write the code for the microcontroller.
- **IDE (Integrated Development Environment):** Keil uVision 5 was the primary development platform for programming and debugging.
- **Simulation Software:** Proteus was used for simulating and testing the circuit design.

## Conclusion

The combination of these sensors, interfaced with an 8051 microcontroller, allowed us to effectively monitor environmental conditions, especially the liquid level in the ground, ensuring a more controlled and suitable environment for plant growth.

This README provides an overview of the project, detailing the purpose, components used, programming language, and software platforms employed.
