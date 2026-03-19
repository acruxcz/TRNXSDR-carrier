# 📡 #TRNXSDR - Open RF Research Platform

**A modular baseboard designed for advanced Software Defined Radio (SDR) ecosystems.**

---

## 📝 Project Overview
The **TRNXSDR** is a robust hardware platform engineered to host and interconnect specialized SDR modules. It acts as the central processing hub, providing high-speed logic, massive memory bandwidth, and versatile connectivity for complex radio applications.

> [!IMPORTANT]
> The **TRNXSDR** is a **Baseboard Platform**. While it provides the processing power and RF routing, it requires external SDR modules connected via the expansion slots for full radio functionality.

## #TRNXSDR Baseboard

<p align="center">
  <img src="Images/TRDP_BaseBoard_with_frame.jpg" width="90%" alt="TRNXSDR BaseBoard">
</p>

---

## 🚀 Key Technical Specifications

### 📟 Processing & Memory
*   **FPGA Core**: High-speed logic for real-time Digital Signal Processing (DSP).
*   **1 GB DDR3 RAM**: High-capacity memory for data buffering and complex waveform processing.
*   **80-pin Module Connectors**: High-density connectors ensuring reliable signal integrity between the baseboard and modules.

### 🌐 Connectivity & I/O
*   **1 Gbit Ethernet (Copper)**: Standard high-speed network integration.
*   **Optical Ethernet (SFP)**: Hardware ready for fiber-optic connection (Planned support for **1 Gbit / 2.5 Gbit+** throughput).
*   **USB-C**: Currently in development—future revisions will support **Power Delivery (PD)** to power the entire board via a single cable.
*   **4 SMA RF Connectors**: On-board SMA connectors for direct and stable antenna connections.

---

## 🛠 Modular Ecosystem & Scalability
The platform is designed to grow. The baseboard features a flexible slot system to accommodate various SDR modules.


| Slot Type | Quantity | Features & Bus Support |
| :--- | :---: | :--- |
| **Primary Baseboard Slots** | **4** | Full support for **High-Speed** interfaces (one dedicated slot) + standard buses. |
| **Expansion Board (Development)** | **+6** | Optimized for **Low-Speed** control buses (SPI, I2C, LVDS). |

## #TRNXSDR with AT86RF215 SDR Module and RFFC5072 Mixer Module + RF Front-End (LNA, PA...) Module

<p align="center">
  <img src="Images/TRDP_SDR_With_AT86RF215_Modul_and_ecosystem.jpg" width="90%" alt="TRNXSDR Ecosystem">
</p>

---

## 🛠 Development Status

- [x] **Baseboard Hardware Design**: Completed (Rev 1.0) — *Functional, with known bugs being addressed.*
- [/] **Hardware Revision 2.0**: In progress (bug fixes and optimizations).
- [/] **Optical Port**: Development in progress.
- [/] **USB-C Power Delivery**: Under active development for future revisions.
