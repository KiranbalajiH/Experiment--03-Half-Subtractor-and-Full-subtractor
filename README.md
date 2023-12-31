# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: KIRANBALAGI H

RegisterNumber:  23002730

Code:

Half subbtractor:

![Exp4 hs code - Copy - Copy](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/ab866491-b86b-4660-bddb-c4837bd545cb)

Full subtractor:

![Exp4 fs code](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/cf8a5d88-f682-48ee-ab87-5beb9bb56b9c)

Truth table:

Full subtractor:

![Exp4 truthtable fs](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/c23d912b-1045-426a-947e-d87533aadb11)

Half subtractor:

![Exp4 truthtable hs](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/f7f4cc92-fe7e-40cc-a62f-caf22bf02b12)

RTL Diagram:

Half subtractor:

![Exp4 hs RTL diagram](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/000a5e8b-3762-4767-b831-163dbfd0def2)

Full subtractor:

![Exp4 fs RTL diagram](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/795ba588-02ec-40a7-a250-af79c5b7b7b8)

Output:

Half subtractor:

![Exp3 hs wave](https://github.com/KiranbalajiH/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149135475/8e0da9c5-32be-4ae8-8223-b1654bf1a12b)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
