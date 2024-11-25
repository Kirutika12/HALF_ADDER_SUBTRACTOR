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


Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B


 
Figure -02 HALF Subtractor

**Truthtable**
### ![ha (2)](https://github.com/user-attachments/assets/30246a0e-8a5d-4c3e-ab64-f46624316803)

### ![hs (2)](https://github.com/user-attachments/assets/ce7b0a64-324e-498d-aae8-545c57768b6a)




**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
### Half Adder:
### module ha(a,b,sum,carry);
### input a,b;
### output sum,carry;
### assign sum=(a^b);
### assign carry=(a&b);
### endmodule

### Half Subtractor:

### module hs(a,b,difference,borrow);
### input a,b;
### output difference,borrow;
### assign difference=(a^b);
### assign borrow=(~a&b);
### endmodule 




### Developed by:Kirutika KR
### RegisterNumber:24001080

**RTL realization output**
### ![funct1](https://github.com/user-attachments/assets/de179bdd-dbe1-4ebd-8d8c-87aef50bf59a)

### ![funct2](https://github.com/user-attachments/assets/bb021940-827a-4221-b996-90e194b86eac)




**Waveform**
### ![ha](https://github.com/user-attachments/assets/ca08a2cc-5373-4b39-adf3-15b7a4a502d9)

### ![hs](https://github.com/user-attachments/assets/b6eac34c-dc8c-47d0-8690-b4f355f42711)




**Result:**
Thus the half adder and half subtractor are studied and the truth table table,logic gates are verified in Quartus using Verilog programming
