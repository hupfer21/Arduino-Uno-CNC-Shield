# 🛠️ Arduino Uno CNC Controller Shield

This project is an open-source CNC controller shield PCB designed for **Arduino Uno**, intended to be used with **Universal G-Code Sender** for controlling small to medium size CNC machines.

The board integrates power management, motor driving and robust industrial-style I/O to simplify CNC controller development.

---

## ✨ Features

- **24V input for all electronics**
  - Single 24V power input for the entire board

- **24V inputs for X, Y, Z limit sensors**
  - Supports both **PNP and NPN** type industrial proximity sensors

- **PNP / NPN selection via DIP switch**
  - Sensor type can be selected without hardware modification
  - Simply configure the onboard DIP switch

- **Opto-isolated limit switch inputs**
  - All limit sensor inputs are electrically isolated using **optocouplers**
  - Improved noise immunity and protection for the microcontroller

- **Integrated power regulation**
  - Onboard **buck converters** step down:
    - 24V → 12V
    - 12V → 5V
  - Powers the Arduino Uno and auxiliary circuits

- **High-current stepper motor driver**
  - Based on **TBD62083** motor driver IC
  - Suitable for driving CNC stepper motors directly

---

## 🧩 Intended Use

This board is designed for:
- DIY CNC machines
- Educational CNC projects
- Low-cost automation and motion control systems

It is fully compatible with **Universal G-Code Sender** running on a host computer and an Arduino Uno running standard CNC firmware (e.g., GRBL).

---

## 📂 Repository Contents

- Schematic files
- PCB layout
- Project libraries
- Documentation

---

## ⚡ Power Requirements

- **Main input:** 24V DC
- Onboard regulation provides:
  - 12V rail
  - 5V rail for Arduino and logic

---

## 📜 License

This project is open-source and free to use, modify and distribute.

---

## 🤝 Contributions

Contributions, suggestions and improvements are welcome!
