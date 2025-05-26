# Traffic_light_controller_Synthesis

## Aim:

Synthesize Traffic Light Controller design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Creating an SDC File

•	In your terminal type “gedit input_constraints.sdc” to create an SDC File if you do not have one.

### Step 3 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

out put new

![Screenshot 2025-05-21 161218](https://github.com/user-attachments/assets/a8ee637a-2f3a-4a34-a0de-232454e0dbb6)


Synthesis RTL Schematic :

![Screenshot 2025-05-21 162922](https://github.com/user-attachments/assets/86abe621-8279-4002-a99e-8a0a102a94de)


Area report:

![Screenshot 2025-05-21 164815](https://github.com/user-attachments/assets/7b356ab0-9dd1-4e7c-9155-08c44f64798a)



Power Report:

![Screenshot 2025-05-21 164052](https://github.com/user-attachments/assets/5954e954-70bc-46d8-98b9-15129dbc4530)

Time report :

![Screenshot 2025-05-21 164412](https://github.com/user-attachments/assets/34a82508-c88b-40dd-93e0-376455ba4dee)



Result:

The generic netlist of Traffic Light Controller has been created, and area, power reports have been tabulated and generated using Genus.
