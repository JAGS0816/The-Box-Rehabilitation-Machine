# Rehabilitation Machine with Encoder
This repository contains the C source code for controlling a rehabilitation machine that uses an encoder to measure position and perform controlled movements. The PIC18F4585 microcontroller processes the encoder information and controls the machine's operation.

# Description
The rehabilitation machine implemented in this code performs controlled movements based on information provided by an encoder. The encoder measures the position, and the system adjusts the movement according to rehabilitation needs. Relevant information is displayed on an LCD, including the current position, elapsed time, and repetition count.

# Features
* Control based on an encoder for position measurement.
* Information display on an LCD.
* Repetition count.
* Power-saving functionality.

# Hardware Requirements
* PIC18F4585 Microcontroller.
* Encoder for position measurement.
* LCD Display.
* Buzzer for acoustic feedback.

# Configuration
Ensure to configure oscillator bits, digital pins, and other settings as needed for your specific hardware. The code has been developed in the MPLAB XC8 environment.

# Usage
1. Clone the repository: git clone https://github.com/JAGS0816/The-Box-Rehabilitation-Machine
2. Open the project in MPLAB X.
3. Compile the code using the XC8 compiler.
4. Load the resulting program into your PIC18F4585 microcontroller.
