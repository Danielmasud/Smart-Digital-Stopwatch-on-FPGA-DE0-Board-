⏱️ Smart Digital Stopwatch on FPGA (DE0 Board)

📝 Project Overview

This project involves the design and implementation of a modular, multi-mode digital stopwatch on an Altera DE0 FPGA board. The system is designed for high-precision time measurement, ranging from daily activities to experiments requiring millisecond accuracy .

🎯 Key Features

Dual Timing Modes:
Standard Mode: Measures time in seconds and minutes.
Reaction Time Mode: High-resolution measurement (0.01s precision) that active as long as the button is held.

Adjustable Display Brightness: Integrated PWM-like control via Switches 6-9 to adjust the 7-segment display intensity based on the environment.

Visual LED Feedback: Green LEDs toggle every second during active measurement to provide real-time status indication.

📸 Visual Gallery

The system in action, displaying elapsed time on the 7-segment displays.

Top-level block diagram showing the integration of frequency dividers, counters, and the display controller.

User Interface: Using switches for brightness control and push-buttons for Start/Stop/Reset.

## Tools & Technologies

- FPGA
- VHDL
- Altera Quartus Prime & DE0 Development Board

---
**Course:** Analog Electronic Circuits | **Institution:** Ruppin Academic Center
