# 🎧 MultiLink Portable Bluetooth Speaker - KiCad Design Files

This repository contains the full **KiCad project files** for the Multilink Portable Bluetooth Speaker designed by **Team 5 – Synergy Electronics** as part of the **Senior Design Capstone at San Diego State University (EE/COMPE 492)**.

## 📦 What’s Inside

This repository includes:
- **Schematic files** for the main and secondary speaker PCBs
- **PCB layout** for a custom 4-layer board
- **Bill of Materials (BOM)**
- **Gerber files** for fabrication
- **Custom footprints and symbols**

> 🎯 These designs were used to build and test a working multilink Bluetooth audio system using STM32/ATmega microcontrollers, BM83 Bluetooth modules, and a custom audio amplification chain.

---

## 🔧 Project Overview

The MultiLink Portable Bluetooth Speaker was designed to:
- Support **multi-speaker synchronized audio** via BM83 Bluetooth modules (host/embedded mode)
- Include **custom power amplifier** and **op-amp gain stages** (LF353 + discrete PA)
- Be powered by **20V DeWalt tool batteries**
- Use **custom enclosures** built from birch wood and plexiglass

🧠 PCB design and layout were done using KiCad 7 and included thermal planning, decoupling, and signal integrity improvements based on EMI/grounding test results.

---

## 🧪 PCB Design Highlights

- ✍️ **4-layer PCB**, designed for both signal integrity and ease of debugging
- 🔁 **Op-amp gain stage** (V=4.3) before power amplifier (V=2.2) for total gain ≈ 9.4 V/V
- 💡 **BM83 Bluetooth module** with UART interface to microcontroller
- 🔌 **Volume, pairing, and power buttons** routed via microcontroller
- 🌡️ **Thermal design** included heatsinks for voltage regulator and amplifier transistors
- 🛠️ Manual fixes applied to final board: jumper wires and capacitor routing corrections

---
🎥 Project Demo: [YouTube Video](https://youtube.com/shorts/QWg84WqX6ao?feature=share)
---

## 👥 Team Members

- **Rocio Lopez** – Project Manager, Lead PCB Designer  
- **Po-Jui Su** – Power Systems Engineer  
- **Ryan Minsky** – Firmware Engineer  
- **Giuseppe Aiello** – Enclosure Designer, Secondary PCB Assembler  
- **Jeffrey Chin** – Project Coordinator  

---

## ⚠️ Disclaimer

This repository contains files for educational and demonstration purposes. No commercial use is authorized.

---
