## Injector Outputs ##

###For 4 cylinder engine sequential injection

####Configure MCU Outputs to Injector MOSFET inputs
/-- 337x260 img/mcu_outputs.png "MCU Outputs to Injection inputs" --/

- Jumper from (Port T4) P20 pin 1 to P34 Pin 1
- Jumper from (Port T5) P20 pin 2 to P34 Pin 2
- Jumper from (Port T6) P20 pin 3 to P34 Pin 3
- Jumper from (Port T7) P20 pin 4 to P34 Pin 4


####Connect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "4 cylinder sequential injection" --/

The injector numbers listed below are the actual firing order, for example, if your engine firing order is 1-3-4-2 you would connect:

- the injector for cylinder #1 to P26 pin 1 (injector #1) 
- the injector for cylinder #3 to P26 pin 2 (injector #2) 
- the injector for cylinder #4 to P26 pin 3 (injector #3)
- the injector for cylinder #2 to P26 pin 4 (injector #4)


###For 6 cylinder engine semi-sequential injection

####Configure MCU Outputs to Injector MOSFET inputs
/-- 337x260 img/mcu_outputs.png "MCU Outputs to Injection inputs" --/

- Jumper from (Port T4) P20 pin 1 to P21 Pin 1
- Jumper from (Port T5) P20 pin 2 to P21 Pin 2
- Jumper from (Port T6) P20 pin 3 to P21 Pin 3


####Configure MCU Outputs to Injector MOSFETs
/-- 248x576 img/injector_jumpers.png "6 cylinder injection inputs" --/

- Jumper from P34 pin 1 to P34 Pin 2 --This allows Q1 and Q2 to be driven by Port T4
- Jumper from P34 pin 3 to P34 Pin 4 --This allows Q3 and Q4 to be driven by Port T5
- Jumper from P34 pin 5 to P34 Pin 6 --This allows Q5 and Q6 to be driven by Port T6


####Connect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "6 cylinder injection" --/


The injector numbers listed below are the actual firing order, for example, if your engine firing order is 1-6-5-4-3-2 you would connect:

- the injector for cylinder #1 to P26 pin 1 (injector #1) 
- the injector for cylinder #6 to P26 pin 2 (injector #2) 
- the injector for cylinder #5 to P26 pin 3 (injector #3)
- the injector for cylinder #4 to P26 pin 4 (injector #4)
- the injector for cylinder #3 to P26 pin 5 (injector #5)
- the injector for cylinder #2 to P26 pin 6 (injector #6)


###For 8 cylinder engine semi-sequential injection

####Configure MCU Outputs to Injector MOSFET inputs
/-- 337x260 img/mcu_outputs.png "MCU Outputs to Injection inputs" --/

- Jumper from (Port T4) P20 pin 1 to P34 Pin 1
- Jumper from (Port T5) P20 pin 2 to P34 Pin 2
- Jumper from (Port T6) P20 pin 3 to P34 Pin 3
- Jumper from (Port T7) P20 pin 4 to P34 Pin 4


####Configure MCU Outputs to Injector MOSFETs
/-- 248x576 img/injector_jumpers.png "8 cylinder injection inputs" --/

- Jumper from P34 pin 1 to P34 Pin 2 --This allows Q1 and Q2 to be driven by Port T4
- Jumper from P34 pin 3 to P34 Pin 4 --This allows Q3 and Q4 to be driven by Port T5
- Jumper from P34 pin 5 to P34 Pin 6 --This allows Q5 and Q6 to be driven by Port T6
- Jumper from P34 pin 7 to P34 Pin 8 --This allows Q7 and Q8 to be driven by Port T7


####Connect Injectors to Injector MOSFETs
/-- 312x572 img/p26.png "8 cylinder injection" --/

The injector numbers listed below are the actual firing order, for example, if your engine firing order is 1-8-4-3-6-5-7-2 you would connect:

- the injector for cylinder #1 to P26 pin 1 (injector #1) 
- the injector for cylinder #8 to P26 pin 2 (injector #2) 
- the injector for cylinder #4 to P26 pin 3 (injector #3)
- the injector for cylinder #3 to P26 pin 4 (injector #4)
- the injector for cylinder #6 to P26 pin 5 (injector #5)
- the injector for cylinder #5 to P26 pin 6 (injector #6)
- the injector for cylinder #7 to P26 pin 5 (injector #7)
- the injector for cylinder #2 to P26 pin 6 (injector #8)


**To configure your freshly installed FreeEMS-powered system, read this [thread](http://forum.diyefi.org/viewtopic.php?f=54&t=1166) and all of the linked threads.

