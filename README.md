# EX 4 FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**


![tt FA1](https://github.com/user-attachments/assets/6ad29df3-e544-4e20-aef7-f7326363317c)


![tt FB2](https://github.com/user-attachments/assets/12b75f0d-0ae2-4487-b646-357ead206492)

**Procedure**

Write the detailed procedure here

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.
   
**Program:**

![full adder code](https://github.com/user-attachments/assets/76aa9a18-ba26-4d42-abba-0bee521106e6)


![full subtractor code](https://github.com/user-attachments/assets/6783495f-4288-420c-97e0-d0eb645b623e)


**RTL Schematic**
![full adder diagram](https://github.com/user-attachments/assets/f0a55554-6326-43b2-a2df-deeb74213d2b)


![full subtractor diagram](https://github.com/user-attachments/assets/1d5d29d4-935f-44a3-aa6c-47cbaa5f6741)

**Output Timing Waveform**
![full adder waveform](https://github.com/user-attachments/assets/07bbb15b-a67f-41ae-bfa8-62dd1aa1ec62)


![full subtractor waveform](https://github.com/user-attachments/assets/b2d59d4b-ee34-4c54-aa13-4bda45d755fc)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



