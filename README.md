# Verilog_implementation_of_Vending_Machine

A circuit that can be used to control a vending machine. The circuit has five inputs: Q (quarter), D (dime), N (nickel), Coin, and Resetn. When a coin is deposited in the machine, a coin-sensing mechanism generates a pulse on the appropriate input (Q, D, or N). To signify the occurrence of the event, the mechanism also generates a pulse on the line Coin. The circuit is reset by using the Resetn signal (active low). When at least 30 cents has been deposited, the circuit activates its output, Z. No change is given if the amount exceeds 30 cents.

A sequence detector is a sequential state machine. In a Moore machine, output depends only on the present state and not dependent on the input (x). Hence in the diagram, the output is written with the states. In a mealy machine, output depends both on the present state and on the input (x). 
The vending machine takes coins as inputs in virtually any sequence and delivers products when Required amount is deposited and provides back the modification that is noticeable entered quantity is more than the price of product.The proposed algorithm is implemented in Verilog HDL and simulated Xilinx ISE simulator.

# SOFTWARE
i) Xilinx ISE 14.7
ii) ISim Simulator

# HDL
Verilog

# Vending Machine 
![image](https://user-images.githubusercontent.com/83426515/165924885-954bd048-5ae2-4981-aab5-bd795119d9df.png)

![Vending_machine](https://user-images.githubusercontent.com/83426515/165924596-89546def-229d-470b-a064-9f0c073e49ec.jpg)

# Finite state Machine diagram
![FSM](https://user-images.githubusercontent.com/83426515/165924740-15451835-2e32-4b29-a05e-d9fbfc372f08.jpeg)

# Implementation Approach
![image](https://user-images.githubusercontent.com/83426515/165925236-778f1c25-6a0d-4ffc-81ce-bb85c58595ea.png)

# RTL Schematic
![image](https://user-images.githubusercontent.com/83426515/165925323-c58803fd-84a9-495c-92ae-a4f581f63b72.png)

# Test run Output
![image](https://user-images.githubusercontent.com/83426515/165925409-a48938bc-dd03-4a20-b478-7483c45b9e6c.png)

# Installation cum Implementation procedure
i)	Open Xilinx ISE 14.7 Project Navigator
ii)	Create a New Project in the desired location with top level source type as HDL
iii)	Device Properties window opens 
Select Family  - Spartan6 
           Device :  XC6SLX9
           Package : CSG324
           Simulator : ISim (VHDL / Verilog)
           Preferred Language : Verilog
iv)	Create New Source File
v)	Select Verilog module with a preferred file name.
vi)	Click Next 
vii)	Click Finish

# References
1. Digital Design | With an Introduction to the Verilog HDL, VHDL, and SystemVerilog| Sixth Edition M. Morris Mano | Emeritus Professor of Computer Engineering California State University, Los Angeles
2. A. Gill, Introduction to the Theory of Finite-state Machines, McGraw-Hill, 1962.
