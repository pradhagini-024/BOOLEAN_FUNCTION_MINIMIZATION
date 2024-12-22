# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions.

![WhatsApp Image 2024-12-21 at 08 56 17_d6f94470](https://github.com/user-attachments/assets/ca675f4f-1205-4177-9731-db1c5a9a2ae0)

![WhatsApp Image 2024-12-21 at 08 56 30_df79a404](https://github.com/user-attachments/assets/305af116-706e-451e-9982-73c87cb706c5)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
```
module funct2(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
```

Developed by: Pradhagini A RegisterNumber: 212224050031*/

**RTL**

![Exp 2 f1 op](https://github.com/user-attachments/assets/d6468b25-179c-46ba-8c06-69ba1c8d6739)

![exp2 f2 op](https://github.com/user-attachments/assets/dd9253a5-7c09-46d5-8727-f4d336128a7a)

**Timing Diagram**

![exp2 f1 wf](https://github.com/user-attachments/assets/cd74b453-df24-44c8-9d82-d44df40e6fad)

![exp2 f2 wf](https://github.com/user-attachments/assets/9970995c-de0b-4943-b3e1-762413061f57)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

