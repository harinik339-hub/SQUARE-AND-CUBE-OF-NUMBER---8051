
# SQUARE AND CUBE OF A NUMBER
# 8051 Square  Program

## AIM
To write and execute an Assembly language program for finding the square of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value to Port 0 (P0).
3. Execute the program.
4. The output square value is stored in Port 2 (P2).

## PROGRAM
```
ORG OOH
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END
```

## OUTPUT
<img width="725" height="271" alt="image" src="https://github.com/user-attachments/assets/e0a8096a-7fa0-4e3f-ae8a-2acc9fca418e" />
<img width="770" height="230" alt="image" src="https://github.com/user-attachments/assets/f44c30ae-8d9f-4322-aaf4-c4f2234b93b5" />


## RESULT
Thus, the square of the given data is calculated using 8051 Keil.

# 8051 Cube  Program

## AIM
To write and execute an Assembly language program for finding the cube of a given data using 8051 microcontroller in Keil software.

## APPARATUS REQUIRED
- Personal computer
- Keil μVision IDE

## ALGORITHM
1. Enter the Assembly language program.
2. Provide the input value.
3. Execute the program.
4. The output cube value is stored in a memory location.

## PROGRAM
```
ORG 00H
MOV DPTR,#4500H
MOVX A,@DPTR
MOV B,A
MUL AB
MOVX B,A
MOVX A,@DPTR
MUL AB
INC DPTR
MOVX @DPTR,A
INC DPTR
MOV A,B
MOVX @DPTR,A
END

```


## OUTPUT
<img width="706" height="316" alt="image" src="https://github.com/user-attachments/assets/120d8f53-fb8e-4262-af7b-a3f66972bc49" />
<img width="762" height="257" alt="image" src="https://github.com/user-attachments/assets/5f867d49-e7d6-493a-a15e-e3c6f7e8b6e1" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
