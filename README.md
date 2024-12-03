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
```
/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
   Developed by:AJIN A
   RegisterNumber:24006578
*/
```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```

**RTL realization**

![EXP2](https://github.com/user-attachments/assets/874c2616-23ba-4f74-a3cd-1b6689faa625)


**Output:**

![EXP2](https://github.com/user-attachments/assets/411f8cb7-3170-4a76-8c7a-9530dc3f8ea3)


**RTL & Timing Diagram**

![EXP2](https://github.com/user-attachments/assets/c597e250-a1e2-472b-90d3-416ca3c73c56)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

