## Injector Outputs ##

####Configure MCU Outputs to Injector MOSFET inputs
/-- 337x260 img/mcu_outputs.png "MCU Outputs to Injection inputs" 

- Jumper from P20 pin 1 to P34 Pin 1
- Jumper from P20 pin 2 to P34 Pin 2
- Jumper from P20 pin 3 to P34 Pin 3
- Jumper from P20 pin 4 to P34 Pin 4

--/

###For 4 cylinder engine

####Connnect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "4 cylinder sequential injection" 

- Connect P26 pin 1 to Injector #1
- Connect P26 pin 2 to Injector #2
- Connect P26 pin 3 to Injector #3
- Connect P26 pin 4 to Injector #4

--/

###For 6 cylinder engine

####Configure MCU Outputs to Injector MOSFETs
/-- 248x576 img/injector_jumpers.png "6 cylinder injection inputs" 

- Jumper from P34 pin 1 to P34 Pin 2 --This allows Q1 and Q2 to be driven by Port T4
- Jumper from P34 pin 3 to P34 Pin 4 --This allows Q3 and Q4 to be driven by Port T5
- Jumper from P34 pin 5 to P34 Pin 6 --This allows Q5 and Q6 to be driven by Port T6

--/

####Connnect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "6 cylinder injection" 

- Connect P26 pin 1 to Injector #1
- Connect P26 pin 2 to Injector #2
- Connect P26 pin 3 to Injector #3
- Connect P26 pin 4 to Injector #4
- Connect P26 pin 5 to Injector #5
- Connect P26 pin 6 to Injector #6

--/

###For 8 cylinder engine

####Configure MCU Outputs to Injector MOSFETs
/-- 248x576 img/injector_jumpers.png "8 cylinder injection inputs" 

- Jumper from P34 pin 1 to P34 Pin 2 --This allows Q1 and Q2 to be driven by Port T4
- Jumper from P34 pin 3 to P34 Pin 4 --This allows Q3 and Q4 to be driven by Port T5
- Jumper from P34 pin 5 to P34 Pin 6 --This allows Q5 and Q6 to be driven by Port T6
- Jumper from P34 pin 7 to P34 Pin 8 --This allows Q7 and Q8 to be driven by Port T7

--/

####Connnect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "8 cylinder injection" 

- Connect P26 pin 1 to Injector #1
- Connect P26 pin 2 to Injector #2
- Connect P26 pin 3 to Injector #3
- Connect P26 pin 4 to Injector #4
- Connect P26 pin 5 to Injector #5
- Connect P26 pin 6 to Injector #6
- Connect P26 pin 5 to Injector #7
- Connect P26 pin 6 to Injector #8

--/

**To configure your freshly installed FreeEMS-powered system, read this [thread](http://forum.diyefi.org/viewtopic.php?f=54&t=1166) and all of the linked threads.

