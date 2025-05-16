# EX NO: 06 - DESIGN & IMPLEMENTATION OF 2-BIT MULTIPLIER USING CADENCE VIRTUOSO

## AIM:
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## TOOLS REQUIRED:
### Cadence Virtuoso Suite:

- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)
- 
### Process Design Kit (PDK):

- CMOS technology library

### Computer System:

- Minimum **4GB RAM** and a **multi-core processor**

## PROCEDURE:
```
### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.
```
### 2. Schematic Design:
```
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.
```
### 3. Simulation:
```
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.
```

## CIRCUIT DIAGRAM:

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## TRUTH TABLE OF 2-BIT MULTIPLIER:

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


### SCHEMATIC OF 2-BIT MULTIPLIER:
![Screenshot (274)](https://github.com/user-attachments/assets/0d2b9c4a-8ed5-46ae-9591-40c9c2d385e9)

## OUTPUT:
### Transient Analysis Output:
![Screenshot (275)](https://github.com/user-attachments/assets/d0d11197-ea7d-4271-940f-7042b95d4ae1)

![image](https://github.com/user-attachments/assets/55864d90-af08-4836-bc90-4cbba80573f8)

![Screenshot (276)](https://github.com/user-attachments/assets/335caf4c-58c6-476e-b1eb-4e61f6067887)

Run Time : 200ns

## RESULT:
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
