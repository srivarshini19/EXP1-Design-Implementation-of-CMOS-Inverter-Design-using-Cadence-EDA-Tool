# Ex No: 01 - Design & Implementation of CMOS Inverter Design Using Cadence EDA Tools

## Aim
The aim is to create and simulate a CMOS inverter circuit with Cadence EDA tools, assess its key electrical properties, and explore foundational CMOS principles, including the design workflow and simulation approaches.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)  
- **Spectre Simulator** (for circuit simulation)  

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
     Open the Cadence Virtuoso tool and set up the working library.
     Create a new schematic cell view for the CMOS Inverter design.
### 2. Schematic Design:
    Select the NMOS and PMOS transistors from the library.
    Connect the NMOS transistor with its source terminal to GND and its drain terminal to the output node.
    Connect the PMOS transistor with its source terminal to VDD and its drain terminal to the same output node as NMOS.
    Join the gate terminals of both transistors to form the input node.
    Connect input voltage sources Vdc and Vpulse
### 3. Simulation:
    Check the Design for Errors and proceed for Simulation
    Launch the Analog Design Environment (ADE).
    Configure transient analysis for time-domain response.
    Set the simulation parameters such as voltage sweep range and step size.
    Use Spectre simulator to perform transient and DC analyses.
### 4. Waveform Analysis:
    Observe the output voltage waveform concerning the input voltage.

## Circuit Diagram:
#### 1. Schematic of CMOS Inverter:

   ![Screenshot (54)](https://github.com/user-attachments/assets/9dc6d11b-1265-4c3c-a769-bab9007dffab)

#### 2. Transient Response Setup:
![Screenshot (62)](https://github.com/user-attachments/assets/bec1f254-05d4-400d-8ebc-49b140a2a7c3)

   
#### 3. Voltage Transfer Characteristic (VTC)  Setup:
![Screenshot (63)](https://github.com/user-attachments/assets/b7e3bed4-afdf-496c-881a-f9c0eb083664)


## Output
#### 1.Transient Analysis Output
![Screenshot (61)](https://github.com/user-attachments/assets/3c8f7b97-7879-4204-8b1d-74ae513289f6)


#### 2.DC Analysis Output
![Screenshot (66)](https://github.com/user-attachments/assets/3cc333a0-72e7-4634-bf7d-9ae7a38d6dc3)


## Results:

1.	Successfully designed the CMOS inverter schematic using Cadence EDA tools.
2.	The simulation results demonstrated the correct logic operation of the inverter, where the output voltage switches between high (Vdd) and low (0V) levels, corresponding to the input voltage transitions.
3.	The Voltage Transfer Characteristic (VTC) curve was plotted, showing the relationship between input and output voltages.











