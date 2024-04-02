# EXPERIMENT--01-ALP-FOR-8086
#### Name : D.Vinitha Naidu
#### Roll no : 212222230175
#### Date of experiment : 





## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required:
8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.	write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

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
org 100h
mov al, 74h
mov bl, 69h
add al,bl
hlt 
ret
```


## Output  

 ![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/66a5b44a-5ddc-4da8-aa2f-cc919e84e336)


## Subtraction   of 8 bit numbers  ALP 
 ```
org 100h
mov al, 84h
mov bl, 63h
sub al,bl
hlt 
ret
```
## Output  

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/6aabc073-2827-48bb-a0c7-a79a9d10ae09)

## Multiplication alp 
```
org 100h
mov al, 75h
mov bl, 32h
mul bl
hlt 
ret
```
 ## Output  

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/25f5b1bd-a5fc-4bac-ad92-5915729d73ae)


## Division alp 
```
org 100h
mov al, 75h
mov bl, 32h
div bl
hlt 
ret
```
## Output  

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/0e3eb7a5-6306-4e00-a5f8-ddfe9dfab07b)

### OR Operation :
```
org 100h
mov al, 32h;
mov bl, 32h;
or al,bl;
hlt 
ret
```
### Output :

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/146d220d-150f-4e51-83fd-c15f38582e92)

### And Operation :
```
org 100
MOV al,32H;
MOV bl,64H;
and al,bl; 
hlt
ret
```
### Output :

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/bb69cda6-2d1c-4997-ab93-5d2f6a15b341)

### NOT Operation :
```
org 100
MOV al,32H;
MOV bl,74H;
not bl; 
hlt
ret
```
### Output:

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/fb07cdf6-aaae-4964-a9d4-931dd9ff2bb8)

### XOR Operation :
```
org 100
MOV al,32H;
MOV bl,74H;
xor al,bl; 
hlt
ret
```
### Output:

![image](https://github.com/Kishore2o/EXPERIMENT--01-ALP-FOR-8086/assets/118679883/4a4f8387-c8bf-44a0-b4fc-4f8f7105e1ab)


### Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully.
 
