# EXPERIMENT--04-ARITHMETIC-AND-LOGICAL-OPERATIONS-USING-LADDER-LOGIC
#  NAME: SURYA R
# REGISTER NUMBER: 212224040339
# DEPARTMENT: CSE
# YEAR: 2025
## Aim:
To understand and implement various arithmetic and logical operations in Programmable Logic Controller (PLC) ladder logic.

## Apparatus Required:
Programmable Logic Controller (PLC): A PLC that supports arithmetic and logical functions.
PLC Programming Software: Software such as RSLogix, TIA Portal, or CX-Programmer.
Computer System: For programming and simulating the PLC ladder logic.
Input Devices: Push buttons or switches to trigger arithmetic and logical operations.
Output Devices: LEDs or other indicators to visualize the results of operations.
Wires and Connectors: For interfacing input/output devices with the PLC.
Power Supply: Appropriate power supply for the PLC and peripherals.
## Theory:
Arithmetic and logical operations in PLC ladder logic are essential for handling complex decision-making and calculations within automation processes. Arithmetic operations (e.g., addition, subtraction, multiplication, division) and logical operations (e.g., AND, OR, NOT) allow PLCs to perform calculations, make comparisons, and control actions based on specific conditions.

## Types of Operations:
Arithmetic Operations:

Addition (ADD): Adds two values and stores the result in a specified memory location.
Subtraction (SUB): Subtracts one value from another.
Multiplication (MUL): Multiplies two values.
Division (DIV): Divides one value by another.
Logical Operations:

AND Operation: The output is TRUE only when all inputs are TRUE.
OR Operation: The output is TRUE when any input is TRUE.
NOT Operation: Inverts the input logic.
Procedure:
Setup the PLC Programming Environment:

Connect the PLC to the computer and launch the PLC programming software.
Ensure all input and output devices are connected to the PLC’s I/O modules.
Create Ladder Logic for Arithmetic Operations:

Addition (ADD):
Create a rung with an input (e.g., push button) linked to an ADD instruction.
Set the operands (e.g., two values) and the destination to store the result.
Subtraction (SUB):
Create a rung with an input linked to a SUB instruction.
Set the values and the destination to store the result.
Multiplication (MUL):
Create a rung with an input linked to a MUL instruction.
Set the values and the destination to store the result.
Division (DIV):
Create a rung with an input linked to a DIV instruction.
Set the values and the destination to store the result.
Create Ladder Logic for Logical Operations:

AND Operation:
Create a rung with two inputs connected in series to simulate an AND operation.
Assign an output to visualize when both inputs are TRUE.
OR Operation:
Create a rung with two inputs connected in parallel to simulate an OR operation.
Assign an output to visualize when any input is TRUE.
NOT Operation:
Create a rung with a single input connected to a NOT function.
Assign an output to visualize the inverted logic.
Simulate the Ladder Logic:

Arithmetic Operations:
Run the simulation in the PLC software. Trigger each operation by pressing the input button, and observe the output values.
Logical Operations:
Simulate the AND, OR, and NOT logic by toggling the inputs and observing the outputs.
Download and Execute:

Download the ladder logic program to the PLC if available and run it.
Test the arithmetic and logical operations with physical push buttons and observe the LEDs or other output devices.


## Outputs:
Arithmetic Operations: Verify that the output shows correct results for addition, subtraction, multiplication, and division.
Logical Operations: Confirm that the output behaves as expected based on the logical conditions (AND, OR, NOT).
##  Simulation Screenshots:
Addition
![image](https://github.com/user-attachments/assets/7ce46b8c-248c-42bc-82bf-6b545a51a24d)
![image](https://github.com/user-attachments/assets/153fb91d-9ccc-42e7-bf65-3c51bc156118)
![image](https://github.com/user-attachments/assets/192e9985-dd3e-448c-a3c9-9066aa1934a9)
![image](https://github.com/user-attachments/assets/73d749d3-45a0-4a5a-8c11-64fb97fd0ceb)

Subtraction
![image](https://github.com/user-attachments/assets/24211adb-fc60-44d8-8391-b282ef3a850a)
![image](https://github.com/user-attachments/assets/313687c9-a35b-4c03-b174-6d38dae295d7)
![image](https://github.com/user-attachments/assets/c22b666b-3125-4a23-8ebe-d2401a8352c8)
![image](https://github.com/user-attachments/assets/41f61f43-148e-4716-8f3c-a909ff20b2e3)

Multiplication
![image](https://github.com/user-attachments/assets/c4e4935a-b533-4240-95b0-4c82d3631051)
![image](https://github.com/user-attachments/assets/1a18689a-c463-4820-af85-272ea4c93915)
![image](https://github.com/user-attachments/assets/f2f20b25-6fda-43f1-ba00-4ef7be909a6f)
![image](https://github.com/user-attachments/assets/3e62a4ad-6aff-4c96-a5eb-e3997f229101)

Division
![image](https://github.com/user-attachments/assets/a654063e-32fa-42cc-b2f1-025cfd76736b)
![image](https://github.com/user-attachments/assets/e2cb5b30-b723-4a22-b20e-f1eb286c2b3e)
![image](https://github.com/user-attachments/assets/15f4fa88-b196-469f-8f36-140a32982587)
![image](https://github.com/user-attachments/assets/b405bbb0-590f-4250-a51b-97e50e26efc9)

## Results:
The ladder logic programs for various arithmetic and logical operations were successfully implemented and tested. The outputs were as expected, demonstrating correct calculation and logical decision-making capabilities. This experiment illustrates the essential role of arithmetic and logical functions in automated processes.
