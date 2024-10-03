# Digital Watch SoC Design on FPGA

This project involves the design, implementation, and programming of a System-on-Chip (SoC) on an **Altera DE1 Cyclone II FPGA board**. The project uses **Quartus**, **Qsys** for synthesis, and **Nios® II Software Developer** for programming in C.

![System Design](https://github.com/user-attachments/assets/1c91f7be-829c-4a14-a4cc-7cb8f59a2952)
# System tool Flow
---
## Project Overview
We designed a digital watch using programmable SoC components, implemented on an FPGA. The watch has functionalities like time display, stopwatch mode, and control inputs for resetting and switching modes.
---

### Hardware Design
![Tool Flow Diagram](https://github.com/Hajjy22/Digital-Watch/assets/135442276/eb32e72c-ab63-4bb4-9f18-2457f5a7357a)

1. **IP Block Selection**: Using Qsys, we chose IP blocks for the components needed in our SoC:
    - NIOS II processor
    - PLL
    - Timers
    - JTAG UART
    - System ID
    - SDRAM, LEDs, Push buttons, Switches, 7-Segment Displays (4 displays)


2. **RTL Generation**: After connecting the components, we generated the RTL code in **VHDL**.

3. **FPGA Design Flow**: The RTL-level design was implemented on the **Altera DE1 Cyclone II** board.

4. **C Programming**: We programmed the SoC using C via the Nios® II Software Developer environment.

### System Components:
- **Push buttons**:  
  - `KEY0`: Reset  
  - `KEY1-3`: Trigger, pause, and stop the watch
- **Switches**: Used to update the watch and toggle between watch and stopwatch mode.
- **7-Segment Displays**: Displays time in the format (HH:MM) and stopwatch in the format (MM:SS).

---

## Results

- **Hardware Design**: Successful integration of all hardware components and implementation on the FPGA.

- **Software Implementation**: The watch functionality was programmed and tested, and the results are displayed on the 7-segment displays.

![Final Results](https://github.com/Hajjy22/Digital-Watch/assets/135442276/1ad7c7b7-d378-4cc9-9494-d5ccb54ad3df)

### Demo:
Check out the video of the running digital watch:  
[Watch Demo](https://github.com/Hajjy22/Digital-Watch/assets/135442276/c10a61b7-a7d1-4704-976c-c5c306f76e02)

---

## Tools and Technologies
- **FPGA**: Altera DE1 Cyclone II
- **Software**: Quartus, Qsys, Nios II Software Developer
- **Languages**: VHDL, C
- **Components**: NIOS II Processor, PLL, Timers, SDRAM, 7-Segment Displays

---

Check the project repository!
