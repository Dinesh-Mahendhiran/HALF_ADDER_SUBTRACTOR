# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**

<img width="550" height="657" alt="{EDA06F51-A59D-4E9D-B596-73613496E8AD}" src="https://github.com/user-attachments/assets/2ed4317b-a9a5-40d9-a20d-d512be607b86" />


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by:Dinesh.M
RegisterNumber: 25007655

**RTL Schematic**
<img width="1078" height="635" alt="{7A5428D9-8B94-497D-B8D9-989919380798}" src="https://github.com/user-attachments/assets/e25cc75b-947d-4949-9b5a-f5d6f545ce36" />
<img width="1070" height="647" alt="{BA3EE41C-7B6F-42F3-A78E-F49D2584C0F6}" src="https://github.com/user-attachments/assets/15aa8edd-7b62-497e-81b1-9e38382db663" />


**Output/TIMING Waveform**
<img width="1077" height="642" alt="{B6376A25-D691-429C-ACC6-921578523B07}" src="https://github.com/user-attachments/assets/0080e6e6-702a-4e98-85d8-b8d72ac0d1a7" />
<img width="1053" height="644" alt="{A801A408-5526-4653-8C4B-E4CE61FD96E9}" src="https://github.com/user-attachments/assets/8fb6020d-4c8a-4b9c-9b58-813dc3f9068a" />

**Result:**
 The program of half added and  half subtration is verifid
