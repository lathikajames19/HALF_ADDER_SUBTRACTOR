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
1).HALF ADDER

![Screenshot 2024-12-03 204651](https://github.com/user-attachments/assets/a256515f-a742-4094-b6b8-ce48b0cfcaa0)

2).HALF SUBTRACTOR

![Screenshot 2024-12-03 204706](https://github.com/user-attachments/assets/14ed46fb-b4d5-4757-9c31-3a0665072dd9)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**

1).HALF ADDER

![Screenshot 2024-12-03 204719](https://github.com/user-attachments/assets/047d6af1-f3b6-463e-ba2d-e35a43f4e303)

2).HALF SUBTRACTOR

![Screenshot 2024-12-03 204733](https://github.com/user-attachments/assets/9314ac15-41db-40da-9a59-8d30ef5a7b8c)


**Output/TIMING Waveform**

1).HALF ADDER

![Screenshot 2024-12-03 204802](https://github.com/user-attachments/assets/1144f941-c67c-48b5-9ac1-3eea527e9513)


2).HALF SUBTRACTOR

![Screenshot 2024-12-03 204821](https://github.com/user-attachments/assets/43ca6e00-5cf2-4ba2-ab08-770906d203f4)

**Result:**
Thus the half adder and the full subtractor circuit is desingned and verified its truth 
table in Quartus using verilog programming.
