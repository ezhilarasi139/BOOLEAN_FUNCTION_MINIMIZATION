# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime*



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**


module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule


module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule


Developed by: Ezhilarasi N RegisterNumber: 24901074 


**RTL realization**
![Screenshot (12)](https://github.com/user-attachments/assets/b1aa1c88-2278-449e-bf3b-f443572b4ea8)


![Screenshot (14)](https://github.com/user-attachments/assets/03d18f25-933d-4601-96eb-84a0ad818229)




**Output:**

![Screenshot (13)](https://github.com/user-attachments/assets/ee5432c9-bc61-46a3-839a-f01172d4b741)

![Screenshot (15)](https://github.com/user-attachments/assets/4592446a-f3e3-46ee-a807-3c9a2ce969e0)



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

