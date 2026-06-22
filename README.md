Link to my Notion page - <h3> 
# ESP32 Solar Motion Light

A solar-powered smart motion light built using an ESP32 microcontroller, PIR motion sensor, rechargeable battery system, and custom 3D-printed enclosure.

The system is designed to operate autonomously using solar energy while maximizing battery life through ESP32 Deep Sleep functionality. When motion is detected, the ESP32 wakes up, activates the flashlight for a configurable period, and then returns to ultra-low-power sleep mode.

This project combines embedded systems, power management, 3D design, and renewable energy technologies into a practical outdoor lighting solution.

---

## Features

### Motion Detection
- HC-SR501 PIR motion sensor
- Detects nearby movement
- Instantly wakes the ESP32 from Deep Sleep

### Ultra Low Power Design
- ESP32 Deep Sleep mode
- RTC GPIO wake-up support
- Timer-based periodic wake checks
- Optimized for long-term battery operation

### Solar Powered
- Solar panel charging system
- Rechargeable lithium battery
- Fully autonomous operation
- No external power source required

### Smart Lighting
- Automatically activates when motion is detected
- Configurable light-on duration
- Automatic shutdown after timeout

### Custom Enclosure
- Fully 3D printed housing
- Weather-resistant design
- Separate compartments for electronics and battery
- Designed for outdoor installation

---

## System Architecture
