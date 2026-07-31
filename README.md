# EXPERIMENT--01-ALP-FOR-8086
## Name : M. Sathyanarayanan
## Roll no : 212224040300
## Date of experiment : 31.07.26

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
ADD ax,bx
MOV [1200H],ax
HLT
```
## Output  
 <img width="627" height="449" alt="Screenshot 2026-07-23 084258" src="https://github.com/user-attachments/assets/2deea019-cb4f-4158-bcec-ce7a4a175b9c" />


## Subtraction   of 8 bit numbers  ALP 
```
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
SUB ax,bx
MOV [1200H],ax
HLT
```
## Output  
<img width="629" height="449" alt="Screenshot 2026-07-23 085205" src="https://github.com/user-attachments/assets/eb9fc5b4-761a-4834-adf4-ed367230daa9" />


## Multiplication alp 
```
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
MUL bx
MOV [1200H],ax
HLT
```
 ## Output  
<img width="631" height="448" alt="Screenshot 2026-07-23 090118" src="https://github.com/user-attachments/assets/f959d7c6-78b1-4ad7-b8e1-8cc57e22bd4b" />


## Division alp 
```
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
DIV bx
MOV [1200H],ax
HLT
```
## Output  
<img width="630" height="446" alt="Screenshot 2026-07-23 090027" src="https://github.com/user-attachments/assets/5dbe78c1-4b0c-43c5-a7a2-b30c2be06be6" />


## And of 8 bit numbers ALP
```assembly
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
AND ax,bx
MOV [1200H],ax
HLT
```
## Output
<img width="632" height="446" alt="Screenshot 2026-07-23 085312" src="https://github.com/user-attachments/assets/946965d3-ab52-46ee-979b-776fc97e365c" />



## OR of 8 bit numbers ALP
```assembly
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
OR ax,bx
MOV [1200H],ax
HLT
```
## Output
<img width="627" height="449" alt="Screenshot 2026-07-23 084258" src="https://github.com/user-attachments/assets/7a51a6be-63a4-40ec-97bf-80e4ce1345a3" />



## NOT of 8 bit number ALP
```assembly
ORG 100H
Mov ax,[1100H]
NOT ax
MOV [1200H],ax
HLT
```
## Output
<img width="630" height="449" alt="Screenshot 2026-07-23 085701" src="https://github.com/user-attachments/assets/cb3e9336-ad51-47a7-93db-cf6f955f4e56" />



## XOR of 8 bit number ALP
```assembly
ORG 100H
Mov ax,[1100H]
MOV bx,[1102H]
XOR ax,bx
MOV [1200H],ax
HLT
```

## Output
<img width="631" height="448" alt="Screenshot 2026-07-23 085411" src="https://github.com/user-attachments/assets/5edb4e52-f711-4435-9529-efe8226a6d22" />



## Result :

The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








