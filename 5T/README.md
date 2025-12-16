
# 5T CMOS OTA using Xschem + Ngspice

This repository contains the design, simulation, and AC analysis of a
**5-Transistor Operational Transconductance Amplifier (5T OTA)**.

## 🔧 Tools Used
- Xschem
- Ngspice
- SKY130 MOS models (cornerMOSlv)

## 📐 Specifications
- Technology: CMOS (SKY130)
- Supply Voltage: 1.5 V
- Topology: 5-Transistor OTA
- Bias Current: 4 µA
- Load Capacitance: 1 pF

## 📊 Simulations
- Operating Point
- AC Gain & Bandwidth
- Gain-Bandwidth Product (GBW)
- Phase Margin (optional)

## ▶️ How to Run
```bash
cd spice
ngspice ota_5t_tb_ac.sp






