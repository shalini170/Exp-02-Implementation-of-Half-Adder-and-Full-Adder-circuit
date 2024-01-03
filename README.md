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
##Half adder

![Screenshot 2024-01-03 023851](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/5b122abe-a919-43f5-bcc0-28a71ee0d0da)

##Full adder

![Screenshot 2024-01-03 023902](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/0120b2db-9bd3-42fb-b947-5a0effb7b374)

##RTL

![Screenshot 2024-01-03 023909](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/e0edd927-8185-4d54-b2b9-e8e0ba2d9012)

![Screenshot 2024-01-03 023918](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/f72dd9a6-1d57-4ee6-8f2e-55c822b8e187)

##Truth table

![Screenshot 2024-01-03 023952](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/c47eb109-5786-4f22-8f67-78f61da6f149)


![Screenshot 2024-01-03 023958](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/4b71af25-9418-4730-b870-f911f9a80a29)

##Output

![Screenshot 2024-01-03 023933](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/661290dc-ca67-44de-8531-d20647a9b7c9)

![Screenshot 2024-01-03 023943](https://github.com/shalini170/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/151901983/8d68b14e-2f50-49ac-a58b-7c5e723b05df)








Developed by: shalini venkatesulu
RegisterNumber:  23001992
*/





### Result 
To design a half adder and full adder circuit and verify its truth table in quatus using verilog programming
