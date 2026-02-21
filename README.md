# Square-Cube-of-a-number-using-8051
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
ORG 00H
MOV R0,#50H
MOV A,@R0
MOV B,@R0
MUL AB
INC R0
MOV @R0,A
END

```

## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-02-11 103215" src="https://github.com/user-attachments/assets/79c7114f-d032-46cf-b8e7-ddba82a6b617" />


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
MOV A,P0
MOV B,AMUL AV
MOV R0,A
MOV A, R0
MOV B, P0
MUL AB
MOV P2,A
END
```
## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-02-11 105814" src="https://github.com/user-attachments/assets/1ddb4156-df98-4815-a6e4-ad5471677609" />

## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.


