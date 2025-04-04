# Door-Lock-system
Electronic Door Lock System Using 8051 Microcontroller
An electronic door lock system was designed and simulated using an 8051 microcontroller in Proteus, integrating a 4x4 matrix keypad for password input and an LCD display for user feedback. Password authentication was implemented using EEPROM storage for data retention. The system was programmed in Embedded C using Keil uVision, ensuring optimized performance for real-time access control. Functionality was tested through various security scenarios, achieving over 90% accuracy in password recognition and response.

Proteus is simulation platform on which Door Lock System is simulated using 8051 micro controller and keypad.

Details:-
1. User will enter the password by using keypad which is interfaced with
 Port 1 of 8051 Micro Controller. 
2. LCD is interfaced with micro controller on Port 2 by 8 data pins.
3. Motor Driver IC L293D is used for controlling DC motor of 12V rating. It is interfaced with Port 3 of micro controller 8051.
4. RS (Register Select) and EN (Enable) Pins of LCD are connected to Port 3 and RW(Read-Write) pin is grounded only for writing purpose on LCD.  
5. 12V battery is used to energies DC motor though IC293D.

Concept:-
1. Password is set 1234 by using programming.
2. If user entered correct password by means of keyboard then LCD will indicate correct and Motor will Rotate to open door.
3. If user entered incorrect password then LCD will display "Incorrect" and motor will not rotate, eventually door will not open.

Keil-Microvision 5 software is used for programming.
![Project Screenshot](![Project Screenshot](assets/image.png)
)
