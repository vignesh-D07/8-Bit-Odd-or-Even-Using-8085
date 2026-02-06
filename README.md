# 8-Bit-Odd-or-Even-Using-8085
# NAME: D VIGNESH
#REGISTER NUMBER: 212224050059

## Aim:
To write an 8085 microprocessor program to check whether a given 8-bit number is odd or even.

## Apparatus Required:
•	Laptop with an internet connection

## Algorithm:
1.	Load the number from a specified memory location into register A.
2.	Perform an AND operation with 01H to check the least significant bit (LSB).
3.	If the result is 0, the number is even; otherwise, it is odd.
4.	Store the result in a specific memory location (odd or even flag).


## Program:
```
LDA 4200H
ANI 01H
JZ L1
MVI A, 01H
JMP L2
L1:MVI A, 02H
L2:STA 4300H
HLT
```
## Verification ODD:
![WhatsApp Image 2026-02-06 at 12 21 15](https://github.com/user-attachments/assets/2c596b1c-ee9d-4163-a0a8-c798766dc6a8)
![WhatsApp Image 2026-02-06 at 12 21 28](https://github.com/user-attachments/assets/c8be59a4-4b6d-4e15-b4f9-53d99621aef1)
![WhatsApp Image 2026-02-06 at 12 21 46](https://github.com/user-attachments/assets/a27123a1-0043-4eae-88b4-81b1dc204dc3)

## Input ODD:
<img width="1900" height="817" alt="Screenshot 2026-02-03 102900" src="https://github.com/user-attachments/assets/da4433bd-47b0-4db0-94e2-39ccd3532629" />

## Output ODD:
<img width="1894" height="807" alt="Screenshot 2026-02-03 102919" src="https://github.com/user-attachments/assets/1aaa8dd9-d6fb-42dd-859d-666005e082a8" />

## Verification EVEN:
![WhatsApp Image 2026-02-06 at 12 22 05](https://github.com/user-attachments/assets/80c155b0-a450-4177-b12c-c0b11c745a7f)
![WhatsApp Image 2026-02-06 at 12 22 27](https://github.com/user-attachments/assets/e09a5e1b-1e3a-4caa-93ca-4e0bf57968d6)

## Input EVEN:

<img width="1902" height="831" alt="Screenshot 2026-02-03 103222" src="https://github.com/user-attachments/assets/56fabb2a-69e2-4d9d-bfe3-e26177ecd0a8" />

## Output EVEN:
<img width="1898" height="826" alt="Screenshot 2026-02-03 103244" src="https://github.com/user-attachments/assets/b60869b5-9040-457f-b862-fbe295f3d331" />

## Result:
The 8085 microprocessor successfully checks whether a given number is odd or even and stores the result in memory.

