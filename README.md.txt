Microwave Oven Control System – Embedded Systems Project
 Project Overview

This project demonstrates the design and simulation of a Microwave Oven control system using a PIC16F877A microcontroller.
It is a menu-driven embedded application that simulates real microwave operations such as mode selection, timing control, start, pause, and stop functionalities.

The project was developed as part of an Embedded Systems Internship, focusing on Embedded C programming, peripheral interfacing, and real-time system behavior.

Internship Objectives

Understand fundamentals of Embedded Systems

Gain hands-on experience with microcontroller programming

Learn peripheral interfacing (Keypad, CLCD, Timers)

Implement real-time embedded applications

Simulate hardware behavior using PICSimLab

 Project Requirements

Display menu options on CLCD

Accept user inputs through Matrix Keypad

Implement cooking modes:

Macro

Grill

Convection

Start / Stop

Timer-based operation

Visual feedback during cooking and completion

Embedded System Description

An embedded system is a dedicated computing system designed to perform a specific function within a larger system.
In this project, the PIC16F877A microcontroller controls inputs, processes user commands, and drives outputs to simulate a microwave oven’s behavior.

System Design
Block Diagram

Matrix Keypad → PIC16F877A → CLCD / Relays / Buzzer

 Microcontroller Board

Microcontroller: PIC16F877A

Clock Frequency: 20 MHz

Peripherals Used:

GPIO Ports

Timers

External Interrupts

CLCD Interface

 Hardware & Software Tools
Hardware Components

PIC16F877A Microcontroller

Matrix Keypad

Character LCD (CLCD)

Buzzer / Relays (Simulated)

Software Tools

MPLAB X IDE

XC8 Compiler

PICSimLab

Embedded C

⚙️ Development Process

Requirement Analysis

System Design & Block Diagram

Peripheral Mapping

Embedded C Coding

Simulation using PICSimLab

Testing and Debugging

Documentation & Presentation

 Implementation Details

Menu displayed on CLCD for mode selection

Keypad used for user input

Timer interrupts manage cooking duration

Status messages shown during operation

Completion message displayed after timer expiry

 Simulation

The complete project is simulated using PICSimLab, demonstrating:

Power ON sequence

Menu navigation

Cooking operation

Completion alert

 Simulation video is included in the repository.

 Key Learning Outcomes

Embedded C programming

Microcontroller peripheral interfacing

Timer and interrupt handling

Real-time embedded system design

Simulation and debugging techniques

 Future Enhancements

Real hardware implementation

Temperature sensor integration

Touch keypad interface

IoT-based remote monitoring

 Author

CH. Koushik Reddy
B.Tech – Electronics & Communication Engineering
Embedded Systems Intern

 Internship Acknowledgement

This project was developed as part of the Embedded Systems Internship under the guidance and training provided by:

Emertxe Information Technologies Pvt. Ltd.

 Repository Contents

Embedded C source code

PICSimLab simulation

Project documentation

Presentation slides

Demo video and screenshots