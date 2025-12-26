# 8051-Thermostat-Control-System

**Development period:** 01/03/2023 – 26/05/2023  
**Tools:** Proteus 8.13, Keil uVision5

Microcontroller-based thermostat system that monitors and regulates room temperature using an analog temperature sensor and a digital humidity sensor. The measured data is processed through an external ADC and displayed on a 16x2 LCD. The user can set a target temperature through buttons, and the system activates a heating element via a relay if the measured temperature is below the desired threshold.

## Main Features
- 8051 microcontroller + ADC0808 + LM016L LCD display
- Analog temperature sensing and digital humidity sensing
- Proteus schematic and full simulation included
- Code implementation in both **Assembly and C**
- Relay-based heater command with real-time comparison logic
- External interrupts for setpoint adjustment (buttons)

## Repository Structure
- `/Proteus` – Simulation files & circuit schematics
- `/Code` – Assembly & C implementations
- `Thermostat.pdf` – Full project documentation

## Keywords
Embedded Systems · 8051 Microcontroller · ADC · Sensors · LCD · Proteus · ASM · C
