## EXPERIMENT  01  ALP on fundamental arithmetic and logical operations 8086

Name :Sathyanarayanan M

Roll no 212224040300

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
~~~
org 100h

mov AX,4325H
mov BX,2233H

add AX,BX  
mov [2000H],AX
mov AX,4325H 

sub AX,BX
mov [2002H],AX
mov AX,4325H
mov CX,2525H

mul CX
mov [2004H],AX
mov AX,2325H
mov CL,05H

div CL
mov [2006H],AX


ret
~~~
```
org 100h

mov BX,3465H;
mov AX,7594H;
AND Ax,BX;
MOV [2000H],AX;


MOV AX,4754H;
MOV CX,3932H;
AND AX,CX; 
NOT CX
MOV [2002H],AX;

MOV AX,4732H;
MOV BX,1124H;
OR  AX,BX;
MOV [2004],AX;

MOV AX,8763H;
MOV BX,7654H;
OR  AX,BX;
NOT BX;
MOV [2006H],AX;

hlt
```




## Output
<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/cc350656-9d80-484d-920d-f6c63b7713bb" />
<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/8b7833c0-aea9-4f74-9462-5f1eb825286e" />
<img width="1918" height="1198" alt="image" src="https://github.com/user-attachments/assets/464bed0e-aabe-4d43-9ff0-e9205436ea3f" />


<img width="1918" height="1198" alt="Screenshot 2026-07-23 083954" src="https://github.com/user-attachments/assets/fe66abbc-9367-4eef-a652-b261932c4695" />
<img width="1918" height="1198" alt="Screenshot 2026-07-23 084012" src="https://github.com/user-attachments/assets/22863f25-afbb-4414-ad61-24d116e6eecc" />
<img width="1918" height="1198" alt="Screenshot 2026-07-23 084022" src="https://github.com/user-attachments/assets/cbb259d1-5dc0-4230-94d6-ef7d3595a50c" />
<img width="1918" height="1198" alt="Screenshot 2026-07-23 084037" src="https://github.com/user-attachments/assets/b2b31788-cbc2-45c8-ad71-f27c49c9ce0c" />


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








