#### MCU Components Installation

These are the necessary components for the MCU to function.

**Step 11 :**
/-- 337x260 img/placeholder_image.png "MCU Oscillator and PLL circuit components" --/ 

Install the following components for the MCU:

- **C1**	*(0.22µF)* located near the top center of the board between PP1 and P20.
- **C2**	*(0.22µF)* located near the center left of the board between PP2 and R60.
- **C3**	*(0.22µF)* located near the center right of the board between C48 and R6.
- **C4**	*(0.22µF)* located near the center left of the board between C44 and D6.
- **C5**	*(0.22µF)* located near the bottom center of the board between D10 and R78.
- **C8**	*(0.22µF)* located near the center right of the board between C6 and C7.
- **C44**	*(0.22µF)* located near the center left of the board between R60 and D8.
- **C6**	*(0.1µF)* located near the center right of the board between BDM and C8.
- **C7**	*(6.8nF)* located near the center right of the board between C8 and P34.
- **C9**	*(680pF)* located near the center right of the board between C3 and C7.
- **C10**	*(12pF)* located near the center right of the board to the right of X1.
- **C11**	*(12pF)* located near the center right of the board to the right of X1.
- **C47**	*(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the left edge of the board. Located near the center left of the board between R11 and R61.
- **C48**	*(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the right edge of the board.  Located near the center right of the board between R3 and C3.
- **D1**	*(LED Yellow)* Direction dependant, orient the **K** lead to the top edge of the board. This is indicated by the short lead of the LED.  Located near the bottom center of the board between R7 and R63.
- **R1**	*(10k ohm)* located near the center right of the board above X1.
- **R2**	*(10k ohm)* located near the center right of the board between R5 and R3.
- **R3**	*(10k ohm)* located near the center right of the board between R2 and C48.
- **R4**	*(10k ohm)* located near the center right of the board between P33 and BDM.
- **R5**	*(10k ohm)* located near the center right of the board between BDM and R2.
- **R8**	*(10k ohm)* located near the center bottom of the board between Load/Run and D1.
- **R6**	*(3.3k ohm)* located near the center right of the board between C3 and P34.
- **R7**	*(1k ohm)* located near the center bottom of the board between X1 and D1.
- **R78**	*(1k ohm)* located near the center bottom of the board above Load/Run.
- **BDM**	*(2x3 0.100" pin strip header)* located near the upper center right of the board between R4 and R35.
- **Load/Run**	*(1x2 0.100" pin strip header)*  located near the center bottom of the board between C5 and R8.
- **X1**	*(16MHz crystal)* located near the center right of the board between R1 and R7.



#### USB UART Components Installation

These are the necessary components for the USB to MCU communications to function.

**Step 12 :**
/-- 337x260 img/placeholder_image.png "USB UART circuit components" --/ 

- **C39**	*(0.1µF)* located near the left center of the board up and right of U6.
- **C41**	*(0.1µF)* located near the top left of the board between J1 and R55.
- **C40**	*(4.7µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the left edge of the board.  Located near the left center of the board between C39 and U6.
- **D33**	*(LED Green)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the short lead of the LED.  Located near the top left of the board between R57 and R59.
- **D34**	*(LED Green)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the short lead of the LED.  Located near the top left of the board between R58 and R59.
- **R57**	*(470 ohm)* located near the top left of the board above D33.
- **R58**	*(470 ohm)* located near the top left of the board above D34.
- **R60**	*(10k ohm)* located near the center left of the board above C44.
- **R79**	*(22 ohm or Ferrite Bead)* located near the top left of the board between J1 and U6.
- Install a jumper wire from **RX** (one of the R60 pads) to **RXB** (near C21).  This bypasses the optocoupler circuit.
- Install a jumper wire from **TX** (near R60) to **TXB** (near C40).  This bypasses the optocoupler circuit.

- Install either **J1**	*(USB-B)* or **J2** *(USB-B Micro)* but **NOT** both!


#### USB UART Optocoupler Components Installation

The following have positions on the PCB, but not required for operation if the wire jumpers mentioned above in Step 12 are used:

**Step 13 :**

If you want to use the optocoupler circuits then **DO NOT** install the jumper wires from **RX** to **RXB** or **TX** to **TXB** mentioned in **Step 12**.

/-- 337x260 img/placeholder_image.png "Optional USB optocoupler circuit components" --/ 

- **R55**	*(2.4k ohm)* Pull up for RESET pin.
- **R56**	*(1k - 2.4k ohm)* Optional for RX Optocoupler
Optional for RX Optocoupler
- **R59**	*(10k ohm)* Optional for TX Optocoupler
- **R61**	*(1k - 2.4k ohm)* Optional for TX Optocoupler
- **U8**	*(Optocoupler)* RX Optocoupler
- **U9**	*(Optocoupler)* TX Optocoupler

**U8** and **U9** may be hand soldered to the board by first applying some solder paste to the PCB pads and then placing the optocoupler on the pads an applying heat from your soldering iron one pad at a time.  You may also install **U8** and **U9** after Step 3 when you install the **FT232RL** chip before the reflow soldering cycle.

**NOTE: The optocouplers and their supporting resistors are OPTIONAL if the end user would like to use an inverter to power their PC while tuning.**

