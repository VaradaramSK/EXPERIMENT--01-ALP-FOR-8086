# EXPERIMENT--01-ALP-FOR-8086
Name : Varadaram SK

Roll no : 212223040232

Date of experiment : 24/04/2026





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
MOV AX, 1234h
MOV BX, 4567h
ADD AX, BX
HTL
```



## Output  

<img width="717" height="556" alt="Screenshot 2026-04-24 154736" src="https://github.com/user-attachments/assets/0739a498-366f-4e3c-836e-3968b8260662" />


 
## Subtraction   of 8 bit numbers  ALP 
```
MOV ax, 1234h
MOV bx, 7428h
SUB ax, bx
HTL
```

 
## Output  

<img width="1326" height="857" alt="sub screenshot" src="https://github.com/user-attachments/assets/f940d18f-1dca-4849-a965-de5e5879d72a" />


## Multiplication alp 
```

MOV ax,1234h 
MOV bx,7428h
MUL bx
HTL

```

 ## Output  



<img width="1377" height="850" alt="experiment 3" src="https://github.com/user-attachments/assets/c4651790-c42a-4ffd-a4a3-d383a3e2ded5" />



## Division alp 
```
MOV ax, 1234h
MOV bx, 4567h
DIV bx
HTL
```

## Output 


<img width="1408" height="907" alt="division screenshot" src="https://github.com/user-attachments/assets/aee9b1e2-08fd-427a-a4d6-b76711e5fe51" />


## And of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
AND AL,BL
HLT
```
## output 

![Screenshot 2025-02-28 085825](https://github.com/user-attachments/assets/72f146a3-28ac-4ca7-9213-7012013e09f3)

## OR of 8 bit numbers ALP
```
MOV AL,33H
MOV BL,44H
OR AL,BL
HLT
```
## output

![Screenshot 2025-02-28 090133](https://github.com/user-attachments/assets/db5ba230-8656-46ee-bfbc-4aa468ae1730)

## NOT of 8 bit number ALP
```
MOV AL,65H
NOT AL
HLT
```

## output
![Screenshot 2025-02-28 090359](https://github.com/user-attachments/assets/c57eee7a-b6e6-4815-8775-0cc3ec0f4282)



## Result :
The execution of ALP on fundamental arithmetic and logical operations is successfully completed.
 








