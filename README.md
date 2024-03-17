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

Developed by:Ahalya S
RegisterNumber:21222323006
module (A,B,C,D,F1);
input A,B,C,D;
output F1;
wire x1,x2,x3,x4,x5;
assign x1=(~A)&(~B)&(~C)&(~D);
assign x2=(A)&(~C)&(~D);
assign x3=(~B)&(C)&(~D);
assign x4=(~A)&(B)&(C)&(D);
assign x5=(B)&(~C)&(D);
assign F1=x1|x2|x3|x4|x5;
endmodule
```

Developed by: AUGUSTINE J

RegisterNumber: 212222240015

### Logic Gate:
![image](https://github.com/Augustine0306/BOOLEAN_FUNCTION_MINIMIZATION/assets/119404460/7c1f04ad-6d71-44b9-ba3a-7b27d93c3d5d)
### Waveform:
![image](https://github.com/Augustine0306/BOOLEAN_FUNCTION_MINIMIZATION/assets/119404460/f4aef3dd-69a0-49a1-9cab-68039e2d2098)
### Truth Table 
![image](https://github.com/Augustine0306/BOOLEAN_FUNCTION_MINIMIZATION/assets/119404460/4c61add6-fb50-4288-b7f0-506e523ff1a0)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

