1.	Learn about binary, decimal and hexadecimal numbers
Decimals:
Every digit in a decimal number has a "position", and the decimal point helps us to know which position is which.
The position just to the left of the point is the "Ones" position. If we see a "7" there we know it means 7 ones. Every position further to the left is 10 times bigger, and every position further to the right is 10 times smaller. The Decimal Number System is also called "Base 10", because it is based on the number 10, with these 10 symbols: 0, 1, 2, 3, 4, 5, 6, 7, 8 and 9.
In decimal you count "0,1,2,3,4,5,6,7,8,9,..." but then you run out of symbols! So you add 1 on the left and then start again at 0: 10,11,12, ...

Binary Numbers
Binary Numbers are just "Base 2" instead of "Base 10". So you start counting at 0, then 1, then you run out of digits ... so you start back at 0 again, but increase the number on the left by 1.
	0	 	Start at 0
•	1	 	Then 1
••	10	 	there is no "2" in binary, so start back at 0 ...
... and add one to the number on the left
•••	11	 	 
••••	100	 	start back at 0 again, and add one to the number on the left...
... but that number is already at 1 so it also goes back to 0 ...
... and 1 is added to the next position on the left
•••••	101	 	 
••••••	110	 	 
•••••••	111	 	 
••••••••	1000	 	Start back at 0 again (for all 3 digits),
add 1 on the left
•••••••••	1001	 	And so on!



Hexadecimal Numbers
Hexadecimal numbers are interesting. There are 16 of them! They look the same as the decimal numbers up to 9, but then there are the letters ("A',"B","C","D","E","F") in place of the decimal numbers 10 to 15. So a single Hexadecimal digit can show 16 different values instead of the normal 10.
Hexadecimal Numbers
Hexadecimal numbers are interesting. There are 16 of them!
They look the same as the decimal numbers up to 9, but then there are the letters ("A',"B","C","D","E","F") in place of the decimal numbers 10 to 15.
So a single Hexadecimal digit can show 16 different values instead of the normal 10
Decimal:	0	1	2	3	4	5	6	7	8	9	10	11	12	13	14	15
Hexadecimal:	0	1	2	3	4	5	6	7	8	9	A	B	C	D	E	F


0	 	Start at 0
•	1	 	Then 1
••	2	 	Then 2
 	⋮	 	 
••••••••••
•••••	F	 	Up to F
••••••••••
••••••	10	 	Start back at 0 again, but add 1 on the left
••••••••••
•••••••	11	 	 
••••••••••
••••••••	12	 	 
 	⋮	 	 
••••••••••
••••••••••
••••••••••
•	1F	 	 
••••••••••
••••••••••
••••••••••
••	20	 	Start back at 0 again, but add 1 on the left
••••••••••
••••••••••
••••••••••
•••	21	 	And so on!



2-Translate the year you where born to binary, decimal and hexadecimal:
(94) decimal
(1011100) Binary
(5C) Hexadecimal
3- Translate 51966 into hexadecimal and binary
Binary 1100101011111111
Hexadecimal 6FE
4- Use a Low-level language, for example MIPS assembler
5- Base on the examples and the guide of the low-level language: 
•	5.1 Create a program to add two numbers given by the user 
.data
	number1: .asciiz "\nIngrese el primer numero: "
	number2: .asciiz "\nIngrese el segundo numero: "
.text
	main:
		li $v0, 4
		la $a0, number1
		syscall

		li $v0, 5
		syscall

		move $t0, $v0

		li $v0, 4
		la $a0, number2
		syscall

		li $v0, 5
		syscall

		move $t1, $v0

		li $v0, 1
		move $a0, $t0
		syscall
•	5.2 Create a program that display your name:
.data
    message: .asciiz "\nSu nombre es: Rafael Peraza!\n"
  .text
    main:
      li $v0, 4
      la $a0, message
      syscall
