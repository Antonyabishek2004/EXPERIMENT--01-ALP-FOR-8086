# EXPERIMENT--01-ALP-FOR-8086

## NAME : ANTONY ABISHEK K

## ROLL NO : 212223240009

## DATE OF EXPERIMENT :

## AIM : 

To Write and execute ALP on fundamental arithmetic and logical operations

## COMPONENTS REQUIRED : 

8086  emulator 

## THEORY :

Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

 ## RUNNING THE EMULATOR :
 
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
  
3.	 write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 	

4.	 Compile the program and check for the errors 

5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 

7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,

8.	 

![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)

9.	Click on emulate to start emulation 

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 

![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## PROGRAMS FOR ARITHMETIC  OPERATIONS :

## ADDITION  OF 8 BIT ALP :

```
MOV AX,48c6H
MOV BX,24e8H
ADD AX,BX
RET
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/23b3cb00-9c43-4983-acde-886b0cf0d7cd" />
 
## SUBTRACTION   OF 8 BIT NUMBERS  ALP :

```
MOV AX,89a7H
MOV BX,18f2H
SUB AX,BX
RET
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d7a39238-9047-4fe8-88ce-1ca463a7f74c" />

## MULTIPLICATION   OF 16 BIT NUMBERS  ALP :

```
org 100h
MOV AX,6d42H
MOV BX,387bH
MUL BX
RET
```
 ## OUTPUT :  

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/3dcfa658-ab58-493b-9286-d0cdc9f676e6" />

## DIVISION OF 16 BIT NUMBERS  ALP :

```
MOV AX,5241H
MOV BX,27a1H
DIV BX
RET
```

## OUTPUT :  

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/b7bb8b69-ca15-4691-ba93-210926d1da78" />

## AND OF 16 BIT NUMBERS  ALP :

```
MOV AX,241fH
MOV BX,4372H
AND AX,BX
RET
```

## OUTPUT :  

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/d5803993-040a-48cd-94b0-ef2778b247e0" />

## OR OF 16 BIT NUMBERS  ALP :

```
MOV AX,45d1H
MOV BX,662aH
OR AX,BX
RET
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/5dafbb2e-238a-4205-9753-4a9ac33efb5d" />

## NOT OF 16 BIT NUMBERS  ALP :

```
MOV AX,561cH
NOT AX
RET
```

## OUTPUT :

<img width="1687" height="1069" alt="image" src="https://github.com/user-attachments/assets/d543626e-ebe4-4249-aa9c-928b7e0b0b65" />

## X-OR OF 16 BIT NUMBERS  ALP :

```
org 100h
mov ax, 99h
mov bx, 60h
xor ax,bx

ret
```

## OUTPUT :

<img width="1659" height="1074" alt="image" src="https://github.com/user-attachments/assets/cda73ac7-599f-4c43-b84c-a2799a3c27e1" />

## RESULT :

Thus the execution for ALP on fundamental arithmetic and logical operations in done on 8086 microprocessor. 








