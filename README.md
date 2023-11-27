# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by : HARSHINI R

Register Number : 23002309

Code :

Full Adder : 

![Exp3 fa code](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/19c80ce4-cc55-48cd-8cbf-29d155a409af)

Half Adder : 

![Exp3 ha code](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/dfb70ffa-2445-45be-97cf-89ee0ae0b74c)

Truth Table :

Full Adder :

![Exp3 truthtable (fa)](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/7df987ae-43a9-4b26-be3a-6599252adee7)

Half Adder :

![Exp3 truthtable (ha)](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/8f52ad73-bc8b-4f16-9b7e-00dbce90cbd2)

RTL realization :

Full Adder :

![Exp3 fa RTL diagram](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/3d5b3dca-53ae-42c2-b2b4-466e9cfe1269)

Half Adder :

![Exp3 ha RTL diagram](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/8472b110-01bb-45e1-b721-e6340d45f0cf)

## Output :

Full Adder :

![Exp3 fa wave](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/5f661ac6-259d-4a6a-8dec-e5a8bf7eec2c)

Half Adder :

![Exp3 ha wave](https://github.com/Harshhinii/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148633023/090f5339-b400-49bd-8e62-54f424d66b0a)

### Result:

Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
