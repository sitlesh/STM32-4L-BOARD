# STM32 Custom Development Board (v1.0)

A highly compact, professionally optimized 4-layer custom development board for the STM32 Microcontroller, designed using KiCad. The layout utilizes a dedicated 4-layer stackup to achieve superior signal integrity, low-noise power distribution, and a minimal form factor.

---

## 🎛️ Layer Stackup
* **Top Layer (F.Cu):** High-speed signal routing and component placement.
* **Internal Layer 1 (In1.Cu):** Dedicated Ground Plane (GND) for EMI shielding.
* **Internal Layer 2 (In2.Cu):** Dedicated Power Plane (3.3V) for stable power distribution.
* **Bottom Layer (B.Cu):** Auxiliary signal routing and ground pour.

---

## 🚀 Features
* **Microcontroller:** STM32 (LQFP-48 package).
* **Power & Connectivity:** USB Type-C interface for power and data.
* **Stackup Optimization:** Dedicated internal power/ground planes to minimize loop inductance.
* **Clock System:** External crystal oscillator circuit.
* **User Interface:** On-board programmable push-button and status LED.

---

## 🛠️ Tech Stack & Software
* **EDA Tool:** KiCad v8.0
* **Manufacturing Standards:** DRC Verified (0 Errors, 0 Unconnected Items), Gerber X2 compliant.

---

## 📦 Project Structure
* `/Hardware` - KiCad schematic (`.kicad_sch`) and PCB layout (`.kicad_pcb`) files.
* `/Manufacturing` - Production-ready Gerber and Drill files (`.zip`).
* `/Images` - 3D renders and layout screenshots.

---

## 📸 Design Preview
![PCB Layout]<img width="3450" height="1886" alt="STM32-4L-MCU-BOARD" src="https://github.com/user-attachments/assets/9028cdb0-4734-4a67-a3a3-e0b07ca5e57c" />

*(Note: Rename your screenshot to match this path or update the filename here)*
