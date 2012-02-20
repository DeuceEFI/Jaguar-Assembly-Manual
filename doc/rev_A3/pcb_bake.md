# Baking the Assembled PCB

*BAKING DETAILS*
/-- 337x260 img/placeholder_image.png "" Before bake --/
/-- 337x260 img/placeholder_image.png "" Into the oven we go! --/
/-- 337x260 img/placeholder_image.png "" At 200&deg; the reflow process has begun peaking around 230&deg; --/
/-- 337x260 img/placeholder_image.png "" Time to cool down. 

- Left : Partial assembled PCB with on-board sensors and USB connector removed for mini-USB mod.
- Center : Blank PCB (I forgot to bring the MCU and FTDI chip along with me, so those are missing, will be put on soon).
- Right : Partial assembled PCB with setup for off-board (OEM) sensors.
--/

#### AFTER BAKING INSPECTION

- Check the entire PCB for Solder bridges, especially on **MCU (U1), R62, U7, U4 and all the Qs**
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

