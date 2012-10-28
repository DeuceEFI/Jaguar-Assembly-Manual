# Outputs #

## GM DIS/HEI Ignition System ##

###JP1 and JP2 settings:

- **JP1**	Install jumper so that the middle pin and the pin closest to R35 is jumpered together (ie: grounded)
- **JP2**	Install jumper so that the middle pin and the pin closest to the end of the PCB is jumpered together (ie: grounded)

###Connect the following ignition system connections to the Jaguar board:

- **DIS-Bypass**	Located in the lower left section of the board near R65. This should be connected to the **TAN/BLACK** wire on most GM DIS or HEI modules.
- **IGN-Advance**	Located in the lower left section of the board near R15.  This should be connected to the **WHITE** (EST) wire on most GM DIS or HEI modules.


## Fuel, Fan and Accessory Outputs ##

###Fuel Pump Low Side Driver

This is the only Low Side Driver that is connected to an MCU output.

- **Fuel-**	Located in the upper left section of the board between C29 and D30.  This should be connected to the **GREEN/WHITE** wire that controls the Fuel Pump Relay on most GM vehicles.


###Fan Low Side Driver

This Low Side Driver is NOT connected to an MCU output.

- **FAN-**	Located in the upper left section of the board between R73 and R74.  This should be connected to the negative wire that controls the radiator cooling Fan Relay.  This can also be used to supply a pulse width modulated input to a variable speed fan controller that you supply external to the Jaguar board.  See the [Jaguar] forum for more details.


###Accessory Low Side Driver

This Low Side Driver is NOT connected to an MCU output.

- **ACC-**	Located in the upper left section of the board between D42 and R76.  This should be connected to the negative wire that controls an Accessory Relay, if needed for your application.

An example would be: I am using the **ACC-** output to drive a relay that controls the Torque Convertor Clutch (TCC) (**TAN/BLACK** wire) on my GM Turbo-Hydro 700R4 transmission.  See the [Jaguar] forum for more details.

