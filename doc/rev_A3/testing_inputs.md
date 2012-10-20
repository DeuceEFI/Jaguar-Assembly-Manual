# Testing Inputs

It's important that you verify the correct operation of your input conditioning circuits before attempting to use the device on a vehicle.

## Test BRV Input

 - Connect a 5v DC supply to the pad labeled **BRV-12v**
 - Connect the negative lead from the 5v DC supply to the pad labeled **GND**
 - Open EMStudio or MegaTunix, you should see 5v DC registered for BRV
 - Connect a 12v DC supply to the pad labeled **BRV-12v**
 - Connect the negative lead from the 12v DC supply to the pad labeled **GND**
 - Open EMStudio or MegaTunix, you should see 12v DC registered for BRV


## Testing analog sensor inputs
 
 - Attach a variable voltage source, such as a JimStim, to one of the Jaguar analog sensor inputs.
 - Adjust the simulated sensor and observe the corresponding values changing within EMStudio or MegaTunix.
 - Repeat the process for all analog sensor inputs being used.
	- If there is no change seen within EMStudio or MegaTunix check the following:
		- That you have the correct corresponding analog input.
		- The analog sensor input circuit is correctly assembled. 

