# PPG
PROJECT: Photoplethysmogram (Heart Rate Monitoring Device)
YEAR: 2019
AUTHOR: Sh.SEDGHI, F.JABARI

This code is for a low-cost, portable heart rate monitoring system that uses a pulse sensor to measure the change of blood volume through the finger artery. The signal is then entered into a Schmitt trigger to increase noise immunity and is fed to a low-cost microcontroller (ATmega16) for analysis and display. The microcontroller counts the number of pulses over a fixed time interval and thus obtains the heart rate of the subject. The device can be programmed to display various quantities, such as the average, maximum and minimum rates over a period of time. The software was developed using Code Vision AVR compiler and the simulation was built in Proteus Software. The program is initialized with the Timer 1 frequency with the value of 7.813KHz and the external interrupt of Counter 0 is set. The program includes libraries, initializes variables, defines the interrupt function, configures input-output ports, initializes the LCD and saves the counted number of timer and resets the amounts. The final heart rate is printed on the LCD.
