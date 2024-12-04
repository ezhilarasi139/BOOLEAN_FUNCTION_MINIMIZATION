# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/*

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


Developed by: Ezhilarasi N RegisterNumber:*/24901074 


**RTL realization**
![Screenshot (3)](https://github.com/user-attachments/assets/c564b5ad-7d18-4651-9332-4c8488ec2be5)



**Output:**

![Screenshot (4)](https://github.com/user-attachments/assets/a8a54d49-19a2-4402-b53b-3b951852e086)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

