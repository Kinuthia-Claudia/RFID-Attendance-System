# RFID-Attendance-System

## Introduction

This project simulates an RFID Attendance System where RFID tags are used to mark the attendance of individuals. The system identifies the person by reading their RFID tag and records their attendance status (e.g., "Present" or "Absent"). The system is built and tested using Proteus Professional 8 simulation software.

## Features

    Simulates an RFID reader and tag interaction.
    Logs attendance in real time.
    Displays attendance status on an LCD.
    Can easily be extended with a database for logging purposes.
    Supports multiple RFID tags (students/employees).

## Components

The following components are used in the Proteus simulation:

    RFID Reader: Simulates an RFID reader to scan RFID tags.
    RFID Tags: Represents individuals in the system.
    Microcontroller (e.g., ATmega32): Controls the RFID system and processes attendance.
    LCD Display (16x2): Displays information such as the individual's name and attendance status.
    Buzzer: Used to give auditory feedback on successful scans.
    Power Supply: Provides power to the circuit.
    LEDs: Indicate the success or failure of RFID tag scans.


The circuit includes the following components wired together:

    Microcontroller (ATmega32) connected to the RFID reader and LCD display.
    Power Supply providing regulated power to the components.
    Buzzer and LEDs for feedback.

## Installation and Setup

    Clone this repository to your local machine

    Download and install the software from the official Proteus website.

    Open the Proteus simulation file (.pdsprj) in Proteus.

    Compile and simulate the project:
        Connect the virtual components and code with the microcontroller.
        Compile the code and run the simulation.
        Observe the RFID attendance system in action on the virtual components (LCD, Buzzer, etc.).

    Test the System:
        Simulate different RFID tags by changing tag IDs in the Proteus environment.
        Verify attendance status on the LCD screen.



## License

This project is licensed under the MIT License. See the LICENSE file for more details.
