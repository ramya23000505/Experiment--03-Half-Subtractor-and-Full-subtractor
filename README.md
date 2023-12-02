NAME: RAMYA R

REG NO: 23000505

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

HALF SUBTRACTOR

![Screenshot 2023-12-02 151529](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/fad76d52-938f-4eab-bc45-fb7a204fb309)

FULL SUBTRACTOR

![Screenshot 2023-12-02 151542](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/82857828-6863-4820-a355-69cb02dbeb4f)

## Truthtable

HALF SUBTRACTOR

![Screenshot 2023-12-02 151606](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/136ff627-745e-4ed7-8285-77323b111053)

FULL SUBTRACTOR

![Screenshot 2023-12-02 151614](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/b89ce7f9-398f-4578-8f68-5167199aeeb4)
 
 ##  RTL realization

 HALF SUBTRACTOR

 ![Screenshot 2023-12-02 151626](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/74471d26-9d71-4762-bd90-2e3733b218b0)

FULL SUBTRACTOR

![Screenshot 2023-12-02 151643](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/e96a38be-6f5c-4a69-9716-4bb2f38bcbc4)

## Timing diagram 

HALF SUBTRACTOR

![Screenshot 2023-12-02 151658](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/9f8a2632-a0dd-4c5f-9b6b-3b0325b33e9b)

FULL SUBRATOR

![Screenshot 2023-12-02 151711](https://github.com/ramya23000505/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/149370791/c4c44dc4-ada6-47c5-9097-c350e2ad1f24)

## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
