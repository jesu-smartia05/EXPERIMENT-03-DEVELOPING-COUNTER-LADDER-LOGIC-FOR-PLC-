# EXPERIMENT-03-DEVELOPING-COUNTER-LADDER-LOGIC-FOR-PLC-
## NAME: Jesu Smartia A
## REGISTER NUMBER: 212223110016
## DEPARTMENT: B.E.CSE(IOT)
## YEAR: III

### Aim:
To understand and implement various counter operations in Programmable Logic Controller (PLC) ladder logic.

### Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports counter functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger the counter operations.
Output Devices: LEDs or other indicators to visualize the counter outputs.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.

### Theory:
Counters in PLCs are used to count events or occurrences, such as the number of items passing on a conveyor belt, the number of cycles a machine runs, or how many times a process has started or stopped. Counters are commonly used in automation to perform tasks like stopping a machine after a set number of products or signaling a notification when a count reaches a specific value.

### Types of Counters:
Up Counter (CTU) Functionality:

The up counter counts every time the input condition becomes TRUE (ON). When the accumulated value reaches the preset value, the counter output becomes TRUE. If the reset input is triggered, the counter resets to zero.
Down Counter (CTD) Functionality:

The down counter decreases the count every time the input condition becomes TRUE (ON). When the count reaches zero, the counter output becomes TRUE. The counter can be reset by a reset input to the preset value.
Up/Down Counter (CTUD) Functionality:

The up/down counter can increment or decrement the count based on two different inputs. One input increments the count, while the other decrements it. When the count reaches the preset value or zero, the respective outputs become TRUE. The counter can be reset as required.


### Procedure:
Setup the PLC Programming Environment:
Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Counters:
Up Counter (CTU):

Create a rung with an input (e.g., a push button) linked to a CTU instruction.
Set the preset value (e.g., 10 counts). Assign an output to indicate when the preset value is reached.
Down Counter (CTD):

Create a rung with an input linked to a CTD instruction.
Set the preset value (e.g., 5 counts). Assign an output to indicate when the counter reaches zero.
Up/Down Counter (CTUD):

Create a rung with separate inputs for counting up and counting down.
Set the preset value (e.g., 8 counts). Assign outputs for when the count reaches the preset value or zero.
Simulate the Ladder Logic:
Up Counter (CTU):

Run the simulation in the PLC software. Press the input button repeatedly and observe the counter increment until the preset value is reached, at which point the output activates.
Down Counter (CTD):

Run the simulation, press the input button repeatedly, and observe the counter decrement. When the counter reaches zero, the output activates.
Up/Down Counter (CTUD):

Simulate both the up and down counting inputs. Observe how the counter increments or decrements and how the output is activated when the count reaches the preset value or zero.
Download and Execute:
Download the ladder logic program to the PLC if available and run it.
Test the counters with the physical push buttons and observe the LEDs or other output devices.
### Outputs:
## Counter :
<img width="1877" height="942" alt="Screenshot 2026-02-17 104444" src="https://github.com/user-attachments/assets/65f956ac-8732-45e2-a29a-ef89f83b956a" />

<img width="1915" height="936" alt="Screenshot 2026-02-17 104343" src="https://github.com/user-attachments/assets/ae3cf762-0750-4101-aec8-c392d54e2c7a" />

## Up Counter (CTU): 

<img width="1124" height="366" alt="Screenshot 2026-02-17 105059" src="https://github.com/user-attachments/assets/1fe07891-0faa-4252-b6e4-7c0db4083eaf" />

<img width="1095" height="305" alt="Screenshot 2026-02-17 105345" src="https://github.com/user-attachments/assets/9b0b228f-2f04-4617-b32d-816b5e2e4473" />

## Down Counter (CTD): 
<img width="1840" height="951" alt="Screenshot 2026-02-17 111021" src="https://github.com/user-attachments/assets/9f914727-32b4-4b36-aaf0-ea0cbf2ef3f1" />

<img width="1919" height="1079" alt="Screenshot 2026-02-17 110836" src="https://github.com/user-attachments/assets/3857ed5e-a034-4686-975b-2acd7c98cce1" />

## Up/Down Counter (CTUD): 
<img width="1915" height="1013" alt="Screenshot 2026-02-17 113012" src="https://github.com/user-attachments/assets/b0351a16-af9d-479e-b03a-86125a78a4ef" />

<img width="1857" height="992" alt="Screenshot 2026-02-17 113022" src="https://github.com/user-attachments/assets/cf391a06-d3d7-47a8-a415-6f0be94d4373" />

![WhatsApp Image 2026-02-17 at 11 30 10 AM](https://github.com/user-attachments/assets/0d1d18b7-7787-483f-931d-e36874798d53)

### Results:
The ladder logic programs for Up Counter (CTU), Down Counter (CTD), and Up/Down Counter (CTUD) were successfully implemented and tested. The outputs behaved as expected, indicating correct counting operations. The experiment demonstrated how counters are essential in automation for counting events and managing process sequences.
