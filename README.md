Ex.No: 5 Logic Programming – Factorial of number

DATE:23-09-2024

REGISTER NUMBER : 21222060247

AIM:
To write a logic program for finding the factorial of given number using SWI-PROLOG.

Algorithm:
STEP 1: Start the program
STEP 2: Write a rules for finding factorial of given program in SWI-PROLOG.
a) factorial of 0 is 1 => written as factorial(0,1).
b) factorial of number greater than 0 obtained by recursively calling the factorial function.
STEP 3: Run the program to find answer of query.
STEP 4: Stop the program.

Program:
```
factorial(0,1). factorial(A,B) :-
A > 0, C is A-1, factorial(C,D),
B is A*D.
```

Output:
![image](https://github.com/user-attachments/assets/62e68490-1ff9-40c7-bc81-8b601626dfba)

Result:
Thus the factorial of given number was found by logic programming.


