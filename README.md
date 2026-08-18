# Microplate Reader & Analyzer Controller Board

## 📌 Overview
The **Microplate Reader & Analyzer Controller Board** is a precision measurement, positioning, and optical feedback control PCB engineered for automated ELISA microplate readers and laboratory diagnostic analyzers.

### Key Features:
- **Motion Control & Position Sensing Channels:**
  - `OP-ROT-RD` / `OP-ROT-SHK` / `OP-ROT-INC`: Multi-channel optical encoder and positioning interfaces for reading mechanisms, plate shaking, and incubator transport.
  - `OP-CLOSE-RD` & `OP-Z-RD`: Door closing, limit switching, and Z-axis optical alignment feedback.
- **Signal Conditioning & Processing Circuits:**
  - High-precision operational amplifiers (`U1`, `U2`, `U5`, `U6` in `SO-14` packages) for sensor signal amplification and filtering.
  - Dedicated diagnostic status LEDs (`ROT1`–`ROT6`, `HEAD1`, `SNK1`).
- **Power Management & Drive Capabilities:**
  - Onboard voltage regulation (`U7`) providing multi-rail supply power (`+24V`, `+12V`, `+5V`, `+3.3V`, `GND`).
  - Solenoid / Actuator driver stage (`U4`) with power jump configurations (`JMP-COMP`).
  - High-density IDC system header for central control bus communication.

---

## 📂 Repository Structure

- 📄 [READER_Board_Schematic.pdf](READER_Board_Schematic.pdf) — Full Circuit Schematic Diagram
- 📊 [BOM_READER_Board.xlsx](BOM_READER_Board.xlsx) — Complete Bill of Materials (Component List)
- 🖼️ [3d_top_view_3.jpg](3d_top_view_3.jpg) — 3D PCB Render (Top View)
- 🖼️ [3d_bottom_view_3.png](3d_bottom_view_3.png) — 3D PCB Render (Bottom View)
- 🖼️ [pcb_layout_top_3.png](pcb_layout_top_3.png) — PCB Top Layer Copper & Silkscreen
- 🖼️ [pcb_layout-bottom_2.png](pcb_layout-bottom_2.png) — PCB Bottom Layer Copper & Silkscreen

---

| Schematic Diagram | Bill of Materials (BOM) |
| :--- | :--- |
| 📄 [Download Schematic PDF](READER_Board_Schematic.pdf) | 📊 [View Bill of Materials (BOM)](BOM_READER_Board.xlsx) |

---

## 🖼️ Visuals

### 3D Model Render

| Top View | Bottom View |
| :---: | :---: |
| ![3D Top View](3d_top_view_3.jpg) | ![3D Bottom View](3d_bottom_view_3.png) |

### PCB Layout Design

| Top Layer | Bottom Layer |
| :---: | :---: |
| ![Top Layer](pcb_layout_top_3.png) | ![Bottom Layer](pcb_layout-bottom_2.png) |
