# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

i)module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));

endmodule

ii)
module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


**RTL realization**

F1:


<img width="1455" height="815" alt="Screenshot 2025-10-07 133428" src="https://github.com/user-attachments/assets/955210cb-f98d-47cf-bb1c-53132550a01c" />

F2:

<img width="1270" height="704" alt="Screenshot 2025-10-07 135349" src="https://github.com/user-attachments/assets/80782f80-5345-41cf-a569-597fa9d4fbea" />



**Output:**

**RTL**

**Timing Diagram**

F1:

<img width="1916" height="398" alt="Screenshot 2025-10-07 134925" src="https://github.com/user-attachments/assets/089cb0e4-03ef-4133-bfe9-d3bbcc2aba73" />

F2:

<img width="1897" height="511" alt="Screenshot 2025-10-07 140333" src="https://github.com/user-attachments/assets/97b93299-32bd-4b95-88fc-3ecc73d612ce" />



**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

