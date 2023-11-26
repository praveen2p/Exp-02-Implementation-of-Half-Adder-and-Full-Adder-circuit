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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: 
RegisterNumber:  
*/
Logic symbol & Truthtable
RTL realization

### Output:
![hal add pro](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/5ce7f267-ed73-4294-a1cb-a414f3a45a1e)

![full add pro](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/73184122-3ee1-4f4d-a1a5-24ae53018515)

### RTL
![rtl hal](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/32fc255e-041f-4153-96a6-2f278eafe624)
![rtl full](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/b072aa6f-2358-4bdb-80f1-0c05a1c9c317)

### TIMING DIAGRAM
![hal time](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/e7255d00-02c6-4c6a-b2d2-89cd9c33727c)
![ful time](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/c25c516d-ce4d-4511-b62c-6b564674aaf8)



### TRUTH TABLE 
![TT hal](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/0c88a19d-edcf-49f7-b4d5-c223c6d972fa)

![TT full](https://github.com/praveen2p/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151658061/122d3baa-891d-4890-b47f-312584120162)




### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
