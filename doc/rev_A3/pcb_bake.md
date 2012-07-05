# Baking the Assembled PCB

*BAKING DETAILS*
- Place the completed board(s) in your reflow soldering oven and start the reflow cycle.
- Once the cycle is complete and the board(s) have cooled, remove them from the reflow oven for inspection.


#### AFTER BAKING INSPECTION

- Check the entire PCB for Solder bridges, especially on **MCU (U1), U7, U4 and all the Qs**
- Examine the new solder joints for dryness, this is normally depicted by dull looking solder, it all should be rather shinny.
- Clear any solder beads that may have formed on the PCB, this can easily be performed by using a tooth brush and giving the PCB a quick and careful scrub.

#### AFTER BAKING TESTING

**Testing MCU for solder bridges**

- Set your DMM for measuring resistance 200 ohm range should be OK;
	- Check from one MCU (U1) pin to the next to make sure they are not shorted together.
		- There is one exception, only MCU (U1) pins 85 and 86 should show shorted.
	- Check from one USB UART (U7) pin to the next to make sure they are not shorted together.
		- There is one exception, only USB UART (U7) pins 25 and 26 should show shorted.
	- Check from one MAX9926 (U4) pin to the next to make sure they are not shorted together.
		- There is no exception.
	- Check from one VNN7NV0413TR (Q9-11) pin to the others to make sure they are not shorted together.
		- Also make sure that no pin is shorted to ground.
	- Check from one VND7NV04 (Q1-8) pin to the others to make sure they are not shorted together.
		- Also make sure that no pin is shorted to ground.

