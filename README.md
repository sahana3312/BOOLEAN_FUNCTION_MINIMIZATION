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

1)Type the program in Quartus software.

2)Compile and run the program.

3)Generate the RTL schematic and save the logic diagram.

3)Create nodes for inputs and outputs to generate the timing diagram.

4)For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
```
Developed by:SAHANA S
RegisterNumber:212225040356
```
```
1)
module boolean(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule 
2)
module bool(w,x,y,z,f2); 
input w,x,y,z; 
output f2; 
assign f2=((~y & z)|( w & y )|(x & y)); 
endmodule

```

**RTL realization**

<img width="966" height="431" alt="image" src="https://github.com/user-attachments/assets/3ae8d6f6-f919-4a76-9fe8-083c222bcb74" />

**Output:**

<img width="998" height="433" alt="image" src="https://github.com/user-attachments/assets/3f824e04-6da0-4618-8745-06033729e9cb" />

**RTL**

<img width="1257" height="597" alt="image" src="https://github.com/user-attachments/assets/4075eb96-6447-4ac9-886c-b88d271b2306" />

**Timing Diagram**

<img width="1252" height="666" alt="image" src="https://github.com/user-attachments/assets/e7ad39e5-cdd7-446b-96a6-550b4891fb5e" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming
