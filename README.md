Ex.No: 6 Logic Programming – Towers of Hanoi

DATE:23-09-2024

REGISTER NUMBER : 21222060247

AIM:
To write a logic program to solve Towers of Hanoi problem using SWI-PROLOG.

Algorithm:
Start the program
Write a rules for finding solution of Towers of Hanoi in SWI-PROLOG.
a ) If only one disk => Move disk from X to Y.
b) If Number of disk greater than 0 then
   i)	Move  N-1 disks from X to Z.
   ii)	Move  Nth disk from X to Y
   iii)	Move  N-1 disks from Y to X.
Run the program to find answer of query.

Program:
```
move(1,X,Y,_) :-  
    write('Move top disk from '), 
    write(X), 
    write(' to '), 
    write(Y), 
    nl. 
move(N,X,Y,Z) :- 
    N>1, 
    M is N-1, 
    move(M,X,Z,Y), 
    move(1,X,Y,_), 
    move(M,Z,Y,X).
```

Output:

![image](https://github.com/user-attachments/assets/b6a13bf4-fd12-47ae-950d-a43d8374458c)

Result:

Thus the solution of Towers of Hanoi problem was found by logic programming.




