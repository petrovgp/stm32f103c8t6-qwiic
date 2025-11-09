# STM32F103C8T6 Qwiic-Compatible Breakout Board

A compact and versatile **STM32F103C8T6** breakout board designed in **KiCad 9**, featuring multiple Qwiic-compatible connectors for easy sensor and peripheral integration. Ideal for prototyping, embedded development, and educational use.

## 📸 Board design
![alt text](https://github.com/petrovgp/stm32f103c8t6-qwiic/blob/main/images/stm32f103c8t6-qwiic-front.png?raw=true)
![alt text](https://github.com/petrovgp/stm32f103c8t6-qwiic/blob/main/images/stm32f103c8t6-qwiic-back.png?raw=true)

## 🧠 Features

### ⚡ Core
- **STM32F103C8T6** ARM Cortex-M3 microcontroller (72 MHz, 64 KB Flash, 20 KB RAM)
- Compact and breadboard-friendly **breakout board design**

### 🔋 Power System
- Operable from **3.3 V regulated** or **5 V external input**
- **ME6211C** LDO regulator:
  - 500 mA maximum output current  
  - 100 mV dropout at 100 mA load

### 🔗 Connectivity
- **Qwiic-compatible connectors** for easy plug-and-play I²C expansion:
  - **I²C1 Qwiic port**
  - **I²C2 Qwiic port**
  - **SWD Qwiic port** for programming and debugging
- Clearly labeled GPIO and power pins for easy interfacing

## 🧩 Design Files
All design files were created in **KiCad 9** and production files have been exported with **PCBWay plugin**:
- `schematics/` – full circuit schematics
- `kicad/` – KiCAD 9 project files 
- `kicad/production/` – ready-to-manufacture files (GERBERs + BOM)

Adjustment of production files might be needed. Please check carefully before placing any manufacturing orders.