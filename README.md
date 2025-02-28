#  EX:1 EXECUTION-OF-LOGIC-GATES-USING-PLC-LADDER-PROGRAM


 # NAME :SHARON ARUL BHARATHI J.F
 # REGISTER NUMBER :212224100056
 # DEPARTMENT : CSE CYBER SECURITY
 # YEAR : 1

 
# Aim:
To implement and verify the functioning of basic logic gates (AND, OR, NOT, NAND, NOR, XOR) using a PLC ladder program and simulate the outputs.

# Apparatus Required:
Programmable Logic Controller (PLC) - A PLC with support for ladder logic programming.
PLC Programming Software - Software like RSLogix, TIA Portal, or CX-Programmer.
Computer System - To run the PLC programming software and perform simulations.
Input Devices - Push buttons or switches to simulate inputs (I/O modules).
Output Devices - LEDs or any indicator to visualize the output of logic gates (I/O modules).
Wires and Connectors - For connecting input/output devices to the PLC.
Power Supply - Appropriate power supply for PLC and peripherals.


# Theory:
Logic gates are the fundamental building blocks of digital circuits, and they process binary inputs to produce a binary output. In PLC programming, these logic gates can be implemented using ladder logic, which is a graphical programming language resembling electrical relay logic.

# Basic Logic Gates:
AND Gate:

Function: Outputs HIGH only when all inputs are HIGH.
Ladder Logic: Represented by two or more normally open contacts in series.
OR Gate:

Function: Outputs HIGH when at least one input is HIGH.
Ladder Logic: Represented by two or more normally open contacts in parallel.
NOT Gate:

Function: Outputs the inverse of the input signal.
Ladder Logic: Represented by a normally closed contact.
NAND Gate:

Function: Outputs LOW only when all inputs are HIGH.
Ladder Logic: An AND gate followed by a NOT gate.
NOR Gate:

Function: Outputs LOW when at least one input is HIGH.
Ladder Logic: An OR gate followed by a NOT gate.
XOR Gate:

Function: Outputs HIGH when an odd number of inputs are HIGH.
Ladder Logic: Represented by a combination of AND, OR, and NOT gates.
# Truth Tables:


**AND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   1    |

**OR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   1    |

**NOT Gate:**
| Input | Output |
|-------|--------|
|   0   |   1    |
|   1   |   0    |

**NAND Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |


**NOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   1    |
|   0     |   1     |   0    |
|   1     |   0     |   0    |
|   1     |   1     |   0    |

**XOR Gate:**

| Input A | Input B | Output |
|---------|---------|--------|
|   0     |   0     |   0    |
|   0     |   1     |   1    |
|   1     |   0     |   1    |
|   1     |   1     |   0    |
 
# Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer system and launch the PLC programming software.
Ensure all input and output devices are correctly connected to the PLC’s I/O modules.
Create Ladder Logic Programs:

For each logic gate, create a ladder logic rung that corresponds to the truth table of the gate.
Use normally open (NO) and normally closed (NC) contacts to implement AND, OR, and NOT logic.
For NAND, NOR, and XOR gates, combine the basic gates appropriately in the ladder diagram.
Simulate the Ladder Logic:

Simulate the ladder logic programs in the PLC software.
Toggle the input states and observe the output corresponding to each gate’s truth table.
# Download and Execute:

If available, download the ladder logic program to the PLC and run it.
Verify the outputs by changing the input states using the connected switches and observing the LEDs or output indicators.
Output of Simulation:
For each logic gate, when the inputs are changed according to the truth tables, the corresponding outputs should be observed as follows:
AND Gate: The output LED or indicator should light up only when both inputs are HIGH.
OR Gate: The output should light up when any one or both inputs are HIGH.
NOT Gate: The output should be the inverse of the input state.
NAND Gate: The output should be HIGH except when both inputs are HIGH.
NOR Gate: The output should be HIGH only when both inputs are LOW.
XOR Gate: The output should light up when exactly one input is HIGH.


# SIMULATION RESULTS 
[Screenshot 2025-02-27 103041](https://github.com/user-attachments/assets/dbfa8ae4-e5a3-4588-9aed-902f393c9881)
![Screenshot 2025-02-27 103056](https://github.com/user-attachments/assets/3e9df7b4-8467-40df-9ef0-f5b6ca898600)
![Screenshot 2025-02-27 103108](https://github.com/user-attachments/assets/adc5b20f-c272-4073-8faf-6d2499e91d52)
![Screenshot 2025-02-27 103122](https://github.com/user-attachments/assets/44680b69-9d3a-4de7-90f5-bb4006e651b7)

![Screenshot 2025-02-27 103241](https://github.com/user-attachments/assets/75517efd-1db0-4b7d-9b3a-723f0c94cb14)
![Screenshot 2025-02-27 103255](https://github.com/user-attachments/assets/bfc698ea-9805-4c14-9eca-feaf3246f61f)
![Screenshot 2025-02-27 103309](https://github.com/user-attachments/assets/8bd93b7d-d00e-42e1-abe1-0aa9ec4f124e)
![Screenshot 2025-02-27 103323](https://github.com/user-attachments/assets/bb9ecc2f-fe78-4d07-ba99-40dfa60c2d25)

![Screenshot 2025-02-27 103501](https://github.com/user-attachments/assets/22a47abf-4ff3-419e-b546-01e3234aa754)
![Screenshot 2025-02-27 103517](https://github.com/user-attachments/assets/36b9a54b-b87e-4c30-9c98-ba1a5e7146a0)
![Screenshot 2025-02-27 103532](https://github.com/user-attachments/assets/10f1a2e7-dfd2-4f27-b466-e9b7ef49086c)
![Screenshot 2025-02-27 103543](https://github.com/user-attachments/assets/3bdbcc76-b97f-4b0b-9d49-4002fe8dc1a2)

![Screenshot 2025-02-27 103725](https://github.com/user-attachments/assets/87b45fc6-dc58-4891-a391-6a38f45c2991)
![Screenshot 2025-02-27 103740](https://github.com/user-attachments/assets/d7cea912-cd57-4522-a0fc-eb754a875ca3)
![Screenshot 2025-02-27 103750](https://github.com/user-attachments/assets/7146b0c7-fae7-44ad-bf33-6739593f046d)
![Screenshot 2025-02-27 103805](https://github.com/user-attachments/assets/f7a3a1c1-cd53-4caf-9ab3-8b50aaefd430)

![Screenshot 2025-02-27 103907](https://github.com/user-attachments/assets/df4e4e1a-37ec-4c30-ade1-392f2e2a2c3d)
![Screenshot 2025-02-27 103918](https://github.com/user-attachments/assets/0d2e59a3-689b-4b6f-91ea-8535143ac146)
![Screenshot 2025-02-27 104008](https://github.com/user-attachments/assets/a409ef96-f85f-4e95-bfb1-6cfdc452ef26)
![Screenshot 2025-02-27 104017](https://github.com/user-attachments/assets/e079f8c3-a663-4031-afd0-8fc1bbdace44)



# Results:
The ladder logic programs for each logic gate were successfully implemented and simulated.
The outputs observed matched the expected results as per the truth tables of the respective logic gates.
This experiment demonstrates the effective use of PLCs in executing digital logic operations, which are fundamental to industrial control systems.
