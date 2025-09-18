# EXPERIMENT 01 Assembly Language Program for 8086
#### Name : Jeeva K
#### Roll no : 212223230090
#### Date : 

## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
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

## Addition  of 16 bit ALP 
```
mov ax,2abch
mov bx,1234h
add ax,bx
ret
```


## Output  
<img width="1920" height="1020" alt="Screenshot 2025-08-21 131812" src="https://github.com/user-attachments/assets/c71722c5-b13e-452e-a7cd-050c70e8e019" />

## Subtraction   of 16 bit numbers  ALP
```
mov ax,2abch
mov bx,1234h
sub ax,[bx]
ret
```
## Output 
<img width="1920" height="1020" alt="Screenshot 2025-08-21 133349" src="https://github.com/user-attachments/assets/43f3c82b-e204-4214-be13-f871018953e0" />

## Multiplication alp 

```
mov cx, 2ABCh   
mov dx, 1234h   

mov ax, cx      
mov bx, dx      
mul bx    
ret
```

## Output  
<img width="1920" height="1020" alt="Screenshot 2025-08-21 135813" src="https://github.com/user-attachments/assets/1f4b749d-85fb-409a-81dc-2c7cbf427542" />


## Division alp 
```
mov ax,2abch
mov bx,[1234h]
div bx
ret
```
## Output  
<img width="1920" height="1020" alt="Screenshot 2025-08-21 132256" src="https://github.com/user-attachments/assets/d007234c-5cbe-4174-af7c-1a63bad22dcf" />



## AND alp
```
mov ax,223ch
mov bx,1234h
and ax,bx
hlt
```

## Output 
<img width="1920" height="1020" alt="Screenshot 2025-08-21 132749" src="https://github.com/user-attachments/assets/607091c0-b642-4d3d-b215-7098889f96ff" />


## OR alp
```
mov ax,223ch
mov bx,1234h
or ax,[bx]
hlt
```

## Output
<img width="1920" height="1020" alt="Screenshot 2025-08-21 133101" src="https://github.com/user-attachments/assets/722a3ad1-8971-4c39-9ce1-24ddf5b75595" />


## NOT alp
```
mov bx,[1234h]
not bx
hlt
```

## Output
<img width="1920" height="1020" alt="Screenshot 2025-08-21 134148" src="https://github.com/user-attachments/assets/4d4e73c1-ff69-4ed7-9a5a-23184663f531" />

## X-OR alp
```
mov cx, 2ABCh   
mov dx, 1234h   

mov ax, cx      
mov bx, dx      
xor ax,bx    
hlt
```

## Output
<img width="1920" height="1020" alt="Screenshot 2025-08-21 141312" src="https://github.com/user-attachments/assets/39078a48-6a23-4501-a70b-01ae66b4b9d6" />

## Result :
 
Thus, to write and execute ALP on fundamental arithmetic operations and Logical operations is successful.







