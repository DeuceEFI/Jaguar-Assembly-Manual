#### MCU Components Installation

These are the necessary components for the MCU to function.

**Step 11 :**
/-- 337x260 img/placeholder_image.png "" MCU Oscillator and PLL circuit components. 

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
/-- 337x260 img/placeholder_image.png "" USB circuit components. 

- **C39**	*(0.1µF)*
- **C40**	*(4.7µF)*
- **C41**	*(0.1µF)*
- **D33**	*(LED Green)*
- **D34**	*(LED Green)*
- **R57**	*(470 ohm)*
- **R58**	*(470 ohm)*
- **R79**	*(22 ohm or Ferrite Bead)*
- Install a jumper wire from **RX** (one of the R60 pads) to **RXB** (near C21)
- Install a jumper wire from **TX** (near R60) to **TXB** (near C40)

--/ 
#### USB UART Optional Components Installation

The following have positions on the PCB, but not required for operation (they are available for experimenting):

**Step 13 :**
/-- 337x260 img/placeholder_image.png "" Optional USB circuit components. 


- **R55**	*(2.4k ohm)* Pull up for RESET pin.
- **R56**	*(2.4k ohm)* Optional for the Opto-Isolators
- **R60**	*(10k ohm)* Optional for the Opto-Isolators
- **R59**	*(10k ohm)* Optional for the Opto-Isolators
- **R61**	*(2.4k ohm)* Optional for the Opto-Isolators
- **U8**	*(Opto Isolator)*
- **U9**	*(Opto Isolator)*

--/ 
