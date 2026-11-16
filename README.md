# CAN-Based-Automotive-DashBoard
Developed a CAN-based automotive dashboard using three PIC18F4580 microcontrollers to monitor speed, gear, RPM, and indicator status.

## Project Overview

The **CAN-Based Automotive Dashboard** is an embedded systems project developed using three PIC18F4580 microcontrollers (ECU1, ECU2, and ECU3) that communicate with each other through the Controller Area Network (CAN) protocol.

The system collects vehicle-related information from different ECUs and displays the data in real time on a Character LCD (CLCD).

## System Architecture

The project consists of three Electronic Control Units (ECUs), each performing specific operations.

### ECU1 – Speed and Gear Control
- Reads vehicle speed using an ADC.
- Handles gear selection using a Digital Keypad.
- Transmits speed and gear information through CAN communication.

### ECU2 – RPM and Indicator Control
- Reads engine RPM using an ADC.
- Handles left, right, and parking indicator operations using a Digital Keypad.
- Controls indicator LED blinking.
- Transmits RPM and indicator status through CAN communication.

### ECU3 – Dashboard Display
- Receives vehicle information from ECU1 and ECU2 through CAN.
- Displays speed, gear, RPM, and indicator status on the CLCD.
- Provides a centralized view of vehicle information.

## Technologies and Components Used

- Embedded C
- PIC18F4580 Microcontroller
- Controller Area Network (CAN)
- Analog-to-Digital Converter (ADC)
- Digital Keypad
- Character LCD (CLCD)
- LED Interfacing
- MPLAB X IDE
- XC8 Compiler

## Key Features

- Communication between three ECUs using the CAN protocol.
- Real-time vehicle speed and engine RPM monitoring.
- Gear selection and display.
- Left, right, and parking indicator operations.
- CAN message transmission and reception.
- Centralized dashboard display using CLCD.

## Learning Outcomes

Through this project, I gained practical experience in:

- Embedded C programming.
- PIC18F4580 microcontroller programming.
- ADC configuration and sensor interfacing.
- CAN protocol configuration and communication.
-
