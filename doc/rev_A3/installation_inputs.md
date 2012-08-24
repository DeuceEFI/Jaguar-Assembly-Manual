## Inputs ##

###Connect the following **ground** connections to the engine block:

- **GND**	Located in the lower right of the board near C19.  This is used for the primary battery ground and should be connected directly to the negative battery terminal.
- **GND2**	Located in the upper right of the board near C12.  This is used for the secondary battery ground and should be connected directly to the negative battery terminal.
- **INJ-GND**	Located in the upper left of the board near R41.  This is used for the injector MOSFETs as their primary isolated ground connection.  It should be connected to the engine block.
- **INJ-GND2**	Located in the upper left of the board near R44.  This is used for the injector MOSFETs as their secondary isolated ground connection.  It should be connected to the engine block.
- **OUT-GND**	Located in the upper left of the board near R46.  This is used for the output MOSFETs as their isolated ground connection.  It should be connected to the engine block.

###Connect the following **ground** connections to the engine sensors:

- **Sensor-GND**	Located in the upper right of the board near JP6.  This is used for the TPS sender ground connection and should be connected directly to the TPS sensor.
- **Sensor-GND**	Located in the upper right of the board near C38.  This is used for the primary analog sensor signal ground and should be connected to the engine block.
- **Sensor-GND**	Located in the upper right of the board near C33.  This is used for the secondary analog sensor signal ground and should be connected to the engine block.

###Connect the following **Switched 12v** connections to the Jaguar board:

- **12v-SW**	Located in the right edge of the board near D44.
- **12v-SW2**	Located in the lower left of the board near D18.
- **BRV-12v**	Located in the top center of the board near R29.
- **FAN-12v**	Located in the top left section of the board near R72.
- **FUEL-12v**	Located in the top left section of the board near R53.
- **ACC-12v**	Located in the top left section of the board near R53.

**NOTE:** 12v-SW, 12v-SW2, FAN-12v, FUEL-12v and ACC-12v can be connected to the same source or you may wish to connect 12v-SW and 12v-SW2 to one source and FAN-12v, FUEL-12v and ACC-12v to a separate source, they are only used to illuminate the LEDs for these outputs.

BRV-12v should be connected separately through a relay back to the battery to measure the voltage at the battery only when the key is on.

###Connect the following analog sensor connections to the Jaguar board:

- **IAT**	Located in the upper middle section of the board near R27. This should be connected to the **TAN** wire on most GM vehicles.
- **MAF**	Located in the upper middle section of the board near C28.
- **CHT**	Located in the upper middle section of the board near R31. This should be connected to the **YELLOW** wire on the Coolant Temperature Sensor on most GM vehicles.
- **O2**	Located in the upper right section of the board near R33. This should be connected to the analog linear output of your wideband O2 lamda sensor.
- **TPS**	Located in the upper right section of the board near R34. This should be connected to the **DARK BLUE** wire on the TPS sender on most GM vehicles.
- **TPS-5v**	Located in the top center of the board near D14. This should be connected to the **GREY** wire going to the TPS sender on most GM vehicles.


## RPM/Position Sensors ##

###Connect the following RPM/Position sensor connections to the Jaguar board:

- **CAM+**	Located in the bottom right section of the board near R20. This should be connected to the **BLACK** wire on most GM vehicles that use a Hall Effect sensor.  If you are using a VR input connect the Camshaft **+** VR input here.
- **CAM-**	Located in the bottom right section of the board near R20.  This should not be connected on GM vehicles that use Hall Effect Camshaft position sensors.  If Hall Effect sensors, Optical sensors or digital sensors are used to not connect anything to this pad.  It is only used for a Camshaft **-** VR input.
- **CAM-Shield**	Located in the bottom right section of the board near R57.  This should be connected to the shield of the wiring for the Camshaft VR input sensor.

- **CRANK+**	Located in the bottom right section of the board near R23. This should be connected to the **BLACK** wire on most GM vehicles that use a Hall Effect sensor.  If you are using a VR input connect the Crankshaft **+** VR input here.
- **CRANK-**	Located in the bottom right section of the board near R19.  This should not be connected on GM vehicles that use Hall Effect Crankshaft position sensors.  If Hall Effect sensors, Optical sensors or digital sensors are used to not connect anything to this pad.  It is only used for a Crankshaft **-** VR input.
- **Crank-Shield**	Located in the bottom right section of the board near R12.  This should be connected to the shield of the wiring for the Crankshaft VR input sensor.


**Verify all the analog sensor inputs are functioning properly by opening MTX and observing the analog sensor input values.**

