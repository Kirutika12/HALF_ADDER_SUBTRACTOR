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

![Screenshot 2024-11-17 184205](https://github.com/user-attachments/assets/f09f3624-3341-4075-9df4-59d60433d108)
![Screenshot 2024-11-17 184013](https://github.com/user-attachments/assets/ef9c98e4-003e-4bbc-ab18-0c1e60a7f93f)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

![Screenshot 2024-11-17 194153](https://github.com/user-attachments/assets/ff6cf85a-4e01-4330-958e-7a2da16a882b)
![Screenshot 2024-11-17 194851](https://github.com/user-attachments/assets/61966e87-142d-4272-848a-1bdd865f4127)



/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: RegisterNumber:*/

**RTL Schematic**

![Screenshot 2024-11-17 194335](https://github.com/user-attachments/assets/34c3db55-2f91-46ca-a7fa-ff22c33cbb6f)
![Screenshot 2024-11-17 194921](https://github.com/user-attachments/assets/60253bf7-4097-43f9-81e3-05059464957b)



**Output/TIMING Waveform**

![Screenshot 2024-11-17 194609](https://github.com/user-attachments/assets/7a6a28b1-5b4b-4663-8408-e5af7f97001f)
![Screenshot 2024-11-17 195051](https://github.com/user-attachments/assets/9e70d8c9-31e9-408a-bce8-f25f3bbf8f87)



**Result:**
Thus the half adder and half subtractor are studied and the truth table table,logic gates are verified
