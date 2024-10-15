# RFID-Attendance-System
RFID Attendance System using Proteus Professional 8

This repository contains the files and code for an RFID-based Attendance System simulation created using Proteus Professional 8. The project demonstrates how RFID technology can be used to log attendance in a system, with each RFID tag representing a student or employee.
Table of Contents

    Introduction
    Features
    Components
    Circuit Diagram
    Installation and Setup
    Usage
    Contributing
    License

Introduction

This project simulates an RFID Attendance System where RFID tags are used to mark the attendance of individuals. The system identifies the person by reading their RFID tag and records their attendance status (e.g., "Present" or "Absent"). The system is built and tested using Proteus Professional 8 simulation software.
Features

    Simulates an RFID reader and tag interaction.
    Logs attendance in real time.
    Displays attendance status on an LCD.
    Can easily be extended with a database for logging purposes.
    Supports multiple RFID tags (students/employees).

Components

The following components are used in the Proteus simulation:

    RFID Reader: Simulates an RFID reader to scan RFID tags.
    RFID Tags: Represents individuals in the system.
    Microcontroller (e.g., ATmega32): Controls the RFID system and processes attendance.
    LCD Display (16x2): Displays information such as the individual's name and attendance status.
    Buzzer: Used to give auditory feedback on successful scans.
    Power Supply: Provides power to the circuit.
    LEDs: Indicate the success or failure of RFID tag scans.

Circuit Diagram

The circuit includes the following components wired together:

    Microcontroller (ATmega32) connected to the RFID reader and LCD display.
    Power Supply providing regulated power to the components.
    Buzzer and LEDs for feedback.

Include the Proteus circuit diagram here or provide a link to it.
Installation and Setup

    Clone this repository to your local machine:

    bash

    git clone https://github.com/yourusername/rfid-attendance-system.git

    Install Proteus Professional 8: Download and install the software from the official Proteus website.

    Load the project: Open the Proteus simulation file (.pdsprj) in Proteus.

    Compile and simulate the project:
        Connect the virtual components and code with the microcontroller.
        Compile the code and run the simulation.
        Observe the RFID attendance system in action on the virtual components (LCD, Buzzer, etc.).

    Test the System:
        Simulate different RFID tags by changing tag IDs in the Proteus environment.
        Verify attendance status on the LCD screen.

Usage

    Power up the system.
    Place an RFID tag near the RFID reader in the simulation.
    If the RFID tag is recognized, the person's name and "Present" status will be displayed on the LCD. The buzzer will beep, and a green LED will light up.
    If the RFID tag is unrecognized, a red LED will light up, and no attendance will be recorded.



License

This project is licensed under the MIT License. See the LICENSE file for more details.