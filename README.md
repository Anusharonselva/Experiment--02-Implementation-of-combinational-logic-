# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory
 

## Logic Diagram
## Procedure
## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: S.ANUSHARON

RegisterNumber: 212222240010

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

module exp2f1(A,B,C,D,f1);

input A,B,C,D;

output f1;

assign f1=(~B&~D)|(A&B&~C)|(~A&B&D);

endmodule

F2=xy’z+x’y’z+w’xy+wx’y+wxy

module exp2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=(~y&z)|(x&y)|(w&y);

endmodule 
*/
## RTL realization

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

![exp-2](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/768c0b4c-747c-473c-ac8e-a71a19ff6c97)

F2=xy’z+x’y’z+w’xy+wx’y+wxy

![Screenshot (223)](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/cb83c039-99af-4fad-9fa6-ff94dc8d01c9)

TRUTH TABLE

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![Screenshot (224)](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/f9604373-bc9e-4509-8123-0ee9bb56d211)

F2=xy’z+x’y’z+w’xy+wx’y+wxy
![Screenshot (225)](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/8531b593-ef17-4b79-810b-542038170c8b)

## Output:
## Timing Diagram
F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
![Screenshot (226)](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/0c5c1b01-1036-4113-9c45-e3346f71723c)

F2=xy’z+x’y’z+w’xy+wx’y+wxy

![Screenshot (227)](https://github.com/Anusharonselva/Experiment--02-Implementation-of-combinational-logic-/assets/119405600/cdc2c586-8712-4898-b995-4caadbbaaaee)


## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
