# Installing the Serial Monitor (SM) #

*In the following sections it is assumed that you just completed the last task which completes the assembly of the Jaguar Revision A.3 board.*

## Installing the serial monitor
/-- 337x260 img/usbdm.jpg "" Using BDM pod and installing the FreeEMS loader 
- Connect a BDM pod to the BDM header on your Jaguar board, I used a TBDML pod.
- Power up the Jaguar board.
- I chose to use the **HiWave** debugger (part of the CodeWarrior package) to flash the SM to the MCU:
	- Install [CodeWarrior] to your Windows based computer and search for and run **hiwave.exe**
   	- Upload the serial monitor: in HiWave.exe, click on **TBDML HCS12**->Flash->Load->Choose SM File->Open->OK.
	- Disconnect the BDM now.
--/
*The Serial Monitor should now be installed on your Jaguar board.*

## Verifying correct operation of the Serial Monitor
/-- 337x260 img/placeholder_image.png "" Jumpering the load/run header for SM testing --/

 - Jumper the load/run header and reset power to the board.
 - Connect a USB cable between your computer and the Jaguar board.
 - Using [CuteCom], 
send various [Serial Monitor](http://www.freescale.com/files/microcontrollers/doc/app_note/AN2548.pdf) packets and verify that it responds correctly.

