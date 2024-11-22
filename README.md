# Exp-5: 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![WhatsApp Image 2024-11-22 at 21 52 02_605b084d](https://github.com/user-attachments/assets/ff208195-0467-40af-a3f9-d52336100046)




#### Area report:

![WhatsApp Image 2024-11-22 at 21 52 01_886eb592](https://github.com/user-attachments/assets/ddb44e81-c7db-4eac-98f6-920ce178f059)




#### Power Report:

![WhatsApp Image 2024-11-22 at 21 52 01_fd659cc1](https://github.com/user-attachments/assets/9f2b32f0-339e-447c-a8c7-78540481a17f)




#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
