#### MCU Components Installation

These are the necessary components for the MCU to function.

**Step 11 :**
/-- 337x260 img/placeholder_image.png "MCU Oscillator and PLL circuit components" 

- **C1**	*(0.22µF)*
- **C2**	*(0.22µF)*
- **C3**	*(0.22µF)*
- **C4**	*(0.22µF)*
- **C5**	*(0.22µF)*
- **C6**	*(0.1µF)*
- **C7**	*(6.8nF)*
- **C8**	*(0.22µF)*
- **C9**	*(680pF)*
- **C10**	*(12pF)*
- **C11**	*(12pF)*
- **C44**	*(0.22µF)*
- **C47**	*(10µF)*
- **C48**	*(10µF)*
- **D1**	*(LED Yellow)*
- **R1**	*(10k ohm)*
- **R2**	*(10k ohm)*
- **R3**	*(10k ohm)*
- **R4**	*(10k ohm)*
- **R5**	*(10k ohm)*
- **R6**	*(3.3k ohm)*
- **R7**	*(1k ohm)*
- **R8**	*(10k ohm)*
- **R78**	*(1k ohm)*
- **BDM**	*(2x3 0.100" pin strip header)*
- **X1**	*(16MHz crystal)*

--/ 

#### USB UART Components Installation

These are the necessary components for the USB to MCU communications to function.

**Step 12 :**
/-- 337x260 img/placeholder_image.png "USB UART circuit components" 

- **C39**	*(0.1µF)*
- **C40**	*(4.7µF)*
- **C41**	*(0.1µF)*
- **D33**	*(LED Green)*
- **D34**	*(LED Green)*
- **R57**	*(470 ohm)*
- **R58**	*(470 ohm)*
- **R79**	*(22 ohm or Ferrite Bead)*
- Install a jumper wire from **RX** (one of the R60 pads) to **RXB** (near C21).  This bypasses the optocoupler circuit.
- Install a jumper wire from **TX** (near R60) to **TXB** (near C40).  This bypasses the optocoupler circuit.

--/ 
#### USB UART Optocoupler Components Installation

The following have positions on the PCB, but not required for operation if the wire jumpers mentioned above in Step 12 are used:

**Step 13 :**

If you want to use the optocoupler circuits then **DO NOT** install the jumper wires from **RX** to **RXB** or **TX** to **TXB** mentioned in **Step 12**.

/-- 337x260 img/placeholder_image.png "Optional USB optocoupler circuit components" 

- **R55**	*(2.4k ohm)* Pull up for RESET pin.
- **R56**	*(1k - 2.4k ohm)* Optional for RX Optocoupler
- **R60**	*(10k ohm)* Optional for RX Optocoupler
- **R59**	*(10k ohm)* Optional for TX Optocoupler
- **R61**	*(1k - 2.4k ohm)* Optional for TX Optocoupler
- **U8**	*(Optocoupler)* RX Optocoupler
- **U9**	*(Optocoupler)* TX Optocoupler

**U8** and **U9** may be hand soldered to the board by first applying some solder paste to the PCB pads and then placing the optocoupler on the pads an applying heat from your soldering iron one pad at a time.  You may also install **U8** and **U9** after Step 3 when you install the **FT232RL** chip before the reflow soldering cycle.

**NOTE: The optocouplers and their supporting resistors are OPTIONAL if the end user would like to use an inverter to power their PC while tuning.**
--/ 
