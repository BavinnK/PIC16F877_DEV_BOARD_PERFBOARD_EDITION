# Chimera DevBoard V2.0: Soldered PIC16F887 Development Platform

## 📋 Overview
A custom, hand-soldered embedded platform based on the PIC16F887 architecture. This board serves as a robust environment for bare-metal ECU simulation and real-time telemetry testing.

## 🛠️ Hardware Specification
- **MCU:** PIC16F887 (8-bit Mid-range architecture).
- **Clock:** 20MHz external Quartz crystal.
- **Power Stage:** Integrated L7805 5V regulator with Schottky diode OR-ing for safe dual-power operation (DC Jack + USB).
- **Serial Bridge:** Onboard CH340G USB-to-UART bridge.
- **Construction:** Double-sided perf-board with industrial-grade soldering and exposed GPIO headers.

## ⚡ Technical Highlights
- **Power Integrity:** Designed with dedicated decoupling capacitors for stable logic levels during high-speed switching.
- **Telemetry ready:** Integrated serial path for HIL (Hardware-in-the-Loop) debugging.
- **Resilient Design:** Features a manual RC reset circuit for predictable startup sequences.

## 📸 Media
![photo_3_2026-03-04_20-57-46](https://github.com/user-attachments/assets/1ddbb0f9-0f45-48a9-8623-3b0f7f992fb2)


![photo_2_2026-03-04_20-57-46](https://github.com/user-attachments/assets/1d833c99-6d45-4016-bd79-5e13599479ee)

## Schematics
<img width="803" height="545" alt="Screenshot 2026-03-04 205843" src="https://github.com/user-attachments/assets/39d5dbec-858b-417b-ae53-559e67083599" />

