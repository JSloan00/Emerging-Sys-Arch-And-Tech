# Emerging-Sys-Arch-Tech
## Summarize the project and what problem it was solving.
For this project, I was tasked with creating a program which would use the temperature sensor on my TI Board. When pressing either of the buttons on the board, it would increase or decrease the temperature setpoint. If the actual temperature was less than the setpoint, the LED light would turn on. 
## What did you do particularly well?
I was able to successfully implement all of the drivers and develop functional code. My TI Board did exactly what it was supposed to do. I also feel pretty confident in my use of best practices and organization of the code. 
## Where could you improve?
The project asked for us to use a task scheduler. While I did attempt to implement a task scheduler, I was not successful. I left the code in as a comment because I want to go back and try to figure out how to get it to work. 
## What tools and/or resources are you adding to your support network?
For this program, I used the I2C, GPIO, and UART peripherals to aide me in developing functional code that produced the expected outcomes. 
## What skills from this project will be particularly transferable to other projects and/or course work?
Understanding what an embedded system is and how they work will be very beneficial to me as a software developer. Even if I do not become an embedded system engineer, understanding how it works will help me to understand how they connect with software within a PC or other device. 
## How did you make this project maintainable, readable, and adaptable?
The main way I did this was by adding comments to every part of the code. I explained the purpose of the code and sometimes explained how it worked. I also tried to organize each part of the code in a way that made sense to the order of how things worked. I identified and created variables and #DEFINEs at the beginning of the code, then created my functions to use, then implemented the main function. 
