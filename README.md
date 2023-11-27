# Experiment--02-Implementation-of-combinational-logic
Implementation of combinational logic gates
 
## AIM:
To implement the given logic function verify its operation in Quartus using Verilog programming.
 F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D
F2=xy’z+x’y’z+w’xy+wx’y+wxy
 
 
 
## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime


## Theory :
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output.
Logic gates are electronic circuits which perform logical functions on one or more inputs to
produce one output. F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D F2=xy’z+x’y’z+w’xy+wx’y+wxy
1.AND gate The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are
high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB Y= A.B
2.OR gate The OR gate is an electronic circuit that gives a high output (1) if one or more of its
inputs are high. A plus (+) is used to show the OR operation. Y= A+B

 
## Procedure :
1.Create a project with required entities.
2.Create a module along with respective file name.
3.Run the respective programs for the given boolean equations.
4.Run the module and get the respective RTL outputs.
5.Create university program(VWF) for getting timing diagram.
6.Give the respective inputs for timing diagram and obtain the results

## Program:
/*
Program to implement the given logic function and to verify its operations in quartus using Verilog programming.
Developed by: shivaa palaniyappan
RegisterNumber:  23007210
*/
## code : 
## F1
![Exp2codei](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/70579117-9a46-4297-9f24-23e803af7b6b)
## F2
![Exp2codeii](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/483b483b-b3c0-4e0e-894e-ca6879d79afc)

## RTL :
## F1
![Exp2 f1](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/af4b8f76-0255-41c0-b06c-9307d45a44b6)
## F2
![Exp2 f2](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/de64e526-0712-4ac8-946d-75125ca6ed9c)

## Output:

## Timing Diagram :
## F1
![Exp2 f1 timing](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/9cc7a66c-8170-4af0-93d6-ca89d94cc204)
## F2
![Exp2 f2 timing](https://github.com/shivaa-palaniyappan/Experiment--02-Implementation-of-combinational-logic-/assets/146915611/43fe34f0-dfd0-47e4-a055-77686751f766)

## Result:
Thus the given logic functions are implemented using  and their operations are verified using Verilog programming.
