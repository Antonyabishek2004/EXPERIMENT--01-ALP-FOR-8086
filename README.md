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
 
3. ```
    write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
   ```
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
  MOV AL,88H
  MOV BL,65H
  ADD AL,BL
  HLT
```

## OUTPUT :  

 <img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/f0853919-8a9a-4b40-95f0-cc3d4c029c19" />

## SUBTRACTION OF 8 BIT NUMBERS ALP : 

```
  MOV AL,84H
  MOV BL,63H
  SUB AL,BL
  HLT
```
 
## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/973570b0-8690-4534-b2f1-e7c2f8b9b3f0" />

## MULTIPLICATION ALP :

```
  MOV AL,33H
  MOV BL,44H
  MUL BL
  HLT
```

## OUTPUT :  

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/27acfef6-14c5-4d12-ba2f-31052d6f0b96" />
  
## DIVISON ALP :

```
  MOV AL,68H
  MOV AL,18H
  DIV BL
  HLT
```
## OUTPUT :  

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7c98bd87-3f3a-4d5a-b039-34526a0c5d56" />

## AND OPERATION :

```
MOV AL,68H
MOV BL,18H
AND AL,BL
HLT
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/ae0573a1-3b03-41e5-8bf5-f1f73b15da60" />

## OR OPERATION :

```
MOV AL,68H
MOV BL,18H
OR AL,BL
HLT
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/083c3c31-6a0e-47bb-a455-6b5673078739" />

## EX-OR OPERATION :

```
MOV AL, 68H
MOV BL, 18H
XOR AL, BL
HLT
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/73c9a58c-7023-40bf-912a-6cc4d9515b43" />

## NOT OPERATION :

```
MOV AL,68H
NOT AL
HLT
```

## OUTPUT :

<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/156a0a54-99dd-4051-b45d-b3de38d221a6" />

## RESULT :
 
The given program excuted succesfully.







