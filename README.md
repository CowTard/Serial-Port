SerialPort
==========

Project work for RCOM


### IMPORTANT FOR WINDOWS USERS 
In order to run on windows, you might want to use cygwin and com0com (Only needed if you dont have physical serial ports).
To compile just go to the folder location in cygwin and type 'make'. Then you just need to write './rcom.exe'

## IMPORTANT FOR MAC/LINUX USERS

  For Linux machines, if you dont have a serial port to test, dont worry. It is even more easy to try this out than windows. Just open a terminal, and paste this: 'socat PTY,link=/dev/ttyS4 PTY,link=/dev/ttyS0'. After complete this, you'll need to open two more terminals and running two different programs, one to receive and another to sending. You will still need to type 'make'. Just use ports '0' and '4'.
  I am sorry MAC users, even though some parts of the code were written on an OSX machine, i used a virtual machine with UBUNTU to test it.
