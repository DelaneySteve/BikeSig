# BikeSig
Bike signalling system to be loaded onto the DE1 SoC MCU, simulated on the CPUlator ARM v7 System Simulator.
https://cpulator.01xz.net/?sys=arm-de1soc (be sure to set the language to C) 

Functions:
  
    Switch 0 -> Right turn signal
  
    Switch 1 -> Left turn signal
  
    Push Button 0 -> brakes
  
 An ADC Converter simulates the values on a gyroscope which are used to determine when to turn off the turning signals. 
