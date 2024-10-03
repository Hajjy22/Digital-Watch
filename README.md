# Digital-Watch

Design, implementation then programation of a SoC on FPGA Altera DE1 Cyclone II board using Quartus, Qsys system for synthesis, and Nios® II Software Developer for the programmation in C language(VHDL, Digital electronics, FPGA design...)

SYSTEM TOOL FLOW:
![System](https://github.com/user-attachments/assets/1c91f7be-829c-4a14-a4cc-7cb8f59a2952)

HARDWARE :
 Selection of the predefined IP blocks using the Qsys system and connecting them.
 Generate the RTL code, in VHDL language, of the final design.
 Execution of the FPGA design flow from the RTL-level to the Programmation of the ALTERA DE1 board.
 Programmation, using C language, of the implemented SoC in the FPGA board.
 
![280500167-077ceb59-32b0-45f0-9b19-1030f4edbbde](https://github.com/Hajjy22/Digital-Watch/assets/135442276/eb32e72c-ab63-4bb4-9f18-2457f5a7357a)

The design and implementation phase is about choosing the IP Block of the different components we needed for our programmable SoC: NIOS II processor, PLL, Timers, Jtag uart, and System Id. And also the corresponding IP block of the physical components we used on the FPGA board: SDRAM 8Mo, Red/green LEDs, push buttons, switches, and 7 segment displays (4 displays). Then we linked the ensemble to generate the RTL code that we compiled and implemented on the FPGA ALTERA DE1 board.

SOFTWARE:
 The SoC programming using C language: After successfully implementing the SoC, we used the NIOS II development software to write the program of the controlled watch concerning the specifications below:
Push buttons: KEY0: reset, KEY1-3: Trigger, pause, stop the watch (seconds and minutes).
Switches: 1-9 controls (as required) for watch update and switch the display between watch and stopwatch.
Displays 7 segments: Watch display (time: 2 displays, minutes: 2 displays), stopwatch (minutes: 2 displays, seconds: 2 displays).


Results :
![279822963-3051a5fc-fd0b-4481-9198-a5fbf7584f20](https://github.com/Hajjy22/Digital-Watch/assets/135442276/1ad7c7b7-d378-4cc9-9494-d5ccb54ad3df)


https://github.com/Hajjy22/Digital-Watch/assets/135442276/c10a61b7-a7d1-4704-976c-c5c306f76e02

