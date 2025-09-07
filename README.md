# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS

![image](https://github.com/user-attachments/assets/6fe3965a-47de-47d4-9dd1-0d52054de81b)

### 2. Schematic of Full Custom 2:1 MUX

<img width="1920" height="1080" alt="Screenshot 2025-09-06 111428" src="https://github.com/user-attachments/assets/480beb92-9fc0-48df-9393-136a86f5eb8d" />


### 3. Transient Response Setup

<img width="1920" height="1080" alt="Screenshot 2025-09-06 110756" src="https://github.com/user-attachments/assets/3ca64e0f-1649-4c88-837e-f43b299066ba" />

<img width="1920" height="1080" alt="Screenshot 2025-09-06 111520" src="https://github.com/user-attachments/assets/3d78455b-f7a5-4ae1-ba07-e5806bf11071" />


## Output

### 1. Transient Analysis Output

<img width="1920" height="1080" alt="Screenshot 2025-09-06 111358" src="https://github.com/user-attachments/assets/cdd6a3ad-4126-4ee2-9bf0-0f4a1da7eb8a" />

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
