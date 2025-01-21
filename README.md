Click here https://mud-barge-6df.notion.site/Project-Solar-Motion-Light-1817578929b680738807cfb46f25ef1a?pvs=4

Project Overview
This repository contains resources for designing and implementing a solar-powered motion sensor light system. The project utilizes an ESP32 microcontroller to manage operations, ensuring energy efficiency and autonomous functionality. The system is entirely self-sustaining, powered by a solar panel, and designed for long-term operation without manual intervention.

Contents
Detailed Documentation:

Step-by-step explanation of the project design and system functionality.
Descriptions of all components and their roles in the system.
Assembly instructions and usage guidelines.
3D-Printed Files:

STL files for all enclosures, including the main body, back cover, and bottom housing.
System Design Visuals:

Exploded view diagrams and wiring illustrations.
Components Used
ESP32 Microcontroller: Manages sensor inputs, controls the light, and enters deep sleep for energy efficiency.
PIR Motion Sensor (HC-SR501): Detects motion to trigger the flashlight.
Solar Panel: Harvests energy to charge the battery during the day.
Lithium Rechargeable Battery: Stores energy for nighttime operation.
Boost Converter & Voltage Regulator: Provide stable 5V and 3.3V power for the sensors and ESP32.
NPN Transistor: Acts as a switch to control the flashlight.
Flashlight: The light source triggered by motion.
3D-Printed Files
This repository includes STL files for the following components:

Main Body: Houses the solar panel, cables, PIR sensor, and mount.
Back Cover: Secures the battery holder, boost converter, and voltage regulator.
Bottom Enclosure: Protects the flashlight and ESP32 microcontroller.
How to Use
Download STL Files:
Files are organized by purpose: MainBody.stl, BackCover.stl, BottomEnclosure.stl.
Print Settings:
Material: PLA or PETG.
Layer height: 0.2 mm.
Infill: 20-40%.
Assembly Instructions:
Assemble all components as per the provided diagrams and instructions.
Ensure secure connections and proper wiring.
Future Enhancements
Custom PCB Design: Consolidate components for a cleaner setup.
LDR Integration: Add ambient light detection for smarter operation.
Remote Monitoring: Leverage ESP32’s Wi-Fi capabilities for system updates and alerts.
Conclusion
This project demonstrates a robust and sustainable lighting solution, powered entirely by renewable energy. With its autonomous design and potential for upgrades, it serves as a versatile system for various environments.


i Will more modify it and uploade a better version 
