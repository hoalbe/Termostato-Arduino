Hello, 
I am trying to create a thermostat project with an Arduino ESP32 CP2102 board and a Nextion Inteligente display.
Right now I am having communication problems between the two elements. 
I have managed to comunicate variable data from an LDR connected to an analog input of the ESP32 board. 
What I can't get is to enter a value in a text or numeric field on the Nextion screen and receive it correctly on the arduino's serial monitor. 

The power supply for the ESP32 board comes from the USB port that I have connected to the PC.
The power for the display comes from the 5VDC and 0VDC pins on the ESP32 board itself. 

The serial communication I want to do through the UART Seire2 port on the ESP32 board. 
