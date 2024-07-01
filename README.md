# AutoPark Tally System
## Overview
 This project provides a cost-effective solution for monitoring real-time parking availability. It uses basic electronic components to detect and count the number of cars entering and leaving a parking lot. The system displays the count on 7-segment displays using a BCD to 7-segment decoder.
## Components Used
* LM358N Comparator: Detects car presence by comparing sensor signals.
* 74LS90 Decade Counter: Counts the number of cars entering and leaving.
* 7447 BCD to 7-segment Decoder: Converts the counted numbers into a format suitable for display on 7-segment displays.
* 7-segment Displays (7SEG-COM-AN-Blue and 7SEG-COM-CAT-Blue): Display the car count using either anode or cathode common connection.
## Features
* Real-time Monitoring: Provides instant updates on available parking spaces.
* Customizable Display: Supports both anode and cathode common displays for flexibility.
* Simple Design: Uses straightforward electronic components without complex software algorithms.
## Project Setup
* Circuit Design: Use Proteus 8 software to simulate the circuit design.
* Component Connections: Ensure correct wiring of LM358N, 74LS90, and 7447 components.
* Simulation: Run simulations to verify functionality and troubleshoot any issues.
* Display Testing: Test 7-segment displays with both types of common connections to confirm proper operation.
## Usage
1. Starting the System: Power on the circuit to begin monitoring.
2. Count Display: The 7-segment display will show the current count of available parking spaces.
3. Entering and Leaving: As cars enter or leave, the count updates accordingly on the display.
   ## Credits
- Project Creator: [Shristi Sarkar]
- Date: January 2023
- Software: Proteus 8
