Bite Force Measurement Device:
A project for a portable, ESP32-based device designed to measure bite force, intended for wellness and bio-feedback applications.

Project Overview :
->This open-source project provides the hardware foundation for a handheld device that measures bite force using a Flexiforce sensor. 
->The data is processed by an ESP32-C3 MCU and displayed in real-time on an SPI screen. 
->The device is designed to be a portable, battery-powered,rechargable tool for non-medical, wellness-related bio-feedback and personal data tracking.

Firmware:
This repository contains the hardware design only. The firmware needs to be developed separately using platforms like the ESP-IDF or the Arduino Core for ESP32.

Core firmware tasks would include:
1.  Reading analog values from the Flexiforce sensor via the MCP6004.
2.  Converting ADC values to force units (Newtons or lbs).
3.  Driving the SPI display to show real-time readings.

Design & Development Disclaimer:

1.Hardware Status:
These PCB designs are for prototyping purposes only.
Passed Checks:
The layouts have passed basic ERC (Electrical Rules Check) and DRC (Design Rule Check).

Untested Aspects:
The designs have not been validated for Signal Integrity (SI),Power Integrity (PI), or EMI/EMC.

They are not guaranteed to pass regulatory certifications without further analysis and revisions.
