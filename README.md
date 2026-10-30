# 8-Bit-Arithmetic-Operations-using-8085
## Aim:
To perform 8-bit arithmetic operations such as addition, subtraction, multiplication, and division using the 8085 microprocessor.
Apparatus Required:
•	Laptop with internet connection
## Algorithm:
## For Addition (With Carry Consideration):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Add the contents of registers A and B.
4.	If carry is generated, store carry in 4301H.
5.	Store the sum in memory location 4300H.
## For Subtraction (Considering Greater Number):
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Compare A and B.
4.	If A < B, swap the values of A and B to ensure positive result.
5.	Subtract the content of B from A.
6.	Store the result in memory location 4300H.
## For Multiplication:
1.	Load the first number from memory location 4200H into register A.
2.	Load the second number from memory location 4201H into register B.
3.	Multiply A and B using repeated addition.
4.	Store the result in memory locations 4300H and 4301H (if required for higher bits).
## For Division:
1.	Load the dividend from memory location 4200H into register A.
2.	Load the divisor from memory location 4201H into register B.
3.	Perform division using repeated subtraction.
4.	Store the quotient in 4300H and remainder in 4301H.
## Program:
<img width="862" height="910" alt="image" src="https://github.com/user-attachments/assets/4c9cedd4-22b3-4d9f-9c84-20dfe2a752c1" />

## Output:
<img width="671" height="339" alt="image" src="https://github.com/user-attachments/assets/39acea5c-79d6-4e42-87e5-070e068ad28b" />
<img width="657" height="296" alt="image" src="https://github.com/user-attachments/assets/1a0d4255-c0a3-46f8-9b34-7fd03371d52e" />
<img width="665" height="304" alt="image" src="https://github.com/user-attachments/assets/39b043e5-87cf-4f81-9fb1-15350dd6d8bf" />
<img width="649" height="306" alt="image" src="https://github.com/user-attachments/assets/793d0e40-0802-4876-afa2-b72fbc07d519" />
Final Output Summary
Operation	Input (Example)	Result (Hex)	Result (Decimal)
Addition	10, 2	0CH	12
Subtraction	10, 2	08H	8
Multiplication	10 × 2	14H	20
Division	10 ÷ 2	05H / 00H	5 Quotient / 0 Remainder
## Result:
The 8-bit arithmetic operations using the 8085 microprocessor have been successfully executed and verified using memory access for input and output.
