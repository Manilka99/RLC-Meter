# RLC Meter Project

This project utilizes the Arduino IDE software to code the Atmega328p microcontroller for the creation of an RLC (Resistance, Inductance, and Capacitance) meter. The RLC meter serves as a versatile electronic device capable of precisely measuring each of these parameters independently.

## Introduction

The RLC meter is a meticulously designed electronic device crafted to provide accurate measurements of resistance (R), inductance (L), and capacitance (C). It operates on the Atmega328p microcontroller running at 16MHz, ensuring precise timing for reliable measurements. The inclusion of a crystal oscillator, along with two 22pF capacitors, further enhances signal precision.

## Features

- **Microcontroller**: Powered by the Atmega328p operating at 16MHz.
- **Crystal Oscillator**: Ensures accurate timing for precise measurements.
- **LCD Display**: Features a 16x2 LCD display with an I2C module for clear presentation of measured parameters.
- **User Interaction**: Utilizes a 10k potentiometer connected to the A2 pin of the microcontroller, providing a user-friendly interface divided into three sections for seamless transition between R, L, and C meter sections.

## Purpose

The purpose of this project is to create an ergonomic and user-friendly RLC meter suitable for both novice and experienced users. By prioritizing user experience and clarity in measurement presentation, the RLC meter becomes an indispensable tool for electronic component analysis and measurement.

## Usage

To utilize the RLC meter:
1. Connect the necessary components as per the provided schematic.
2. Upload the Arduino file to the Atmega328p microcontroller using the Arduino IDE.
3. Power on the RLC meter and interact with the device using the potentiometer to navigate between R, L, and C meter sections.
4. Obtain precise measurements of resistance, inductance, and capacitance for electronic component analysis.

## Contribution

Contributions to this project are welcome. If you have suggestions for improvements or encounter any issues, please feel free to open an issue or submit a pull request.
