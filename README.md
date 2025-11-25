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


MOV A,P0 
MOV R0,A 
MOV B,R0 
MUL AB 
MOV P2,A 
END


```

## OUTPUT

<img width="549" height="385" alt="Screenshot 2025-10-27 104525" src="https://github.com/user-attachments/assets/d9d9fc8c-f638-45c1-ae36-bc990190bac6" />

![WhatsApp Image 2025-11-09 at 14 39 22_13b4f346](https://github.com/user-attachments/assets/7e15e5e5-36eb-45eb-9623-e74ae55e6057)



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


MOV A, P0
MOV B, A
MUL AB
MOV R0, A
MOV A, R0
MOV B, P0
MUL AB
MOV P2, A
END

```


## OUTPUT
<img width="468" height="340" alt="image" src="https://github.com/user-attachments/assets/8e23ee29-36b5-4e96-9c74-fc5c8c01653d" />

![WhatsApp Image 2025-11-09 at 14 39 34_13562132](https://github.com/user-attachments/assets/ee6c1dd0-6d2f-4429-9d83-2cae950ad3d7)


## RESULT
Thus, the cube of the given data is calculated using 8051 Keil.
