#### MCU Components Installation

These are the necessary components for the MCU to function.

**Step 11 :**
/-- 337x260 img/oscillator_pll.png "MCU Oscillator and PLL circuit components" --/ 

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
/-- 337x260 img/usb_uart.png "USB UART circuit components" --/ 

- **C39**	*(0.1µF)* located near the left center of the board up and right of U6.
- **C41**	*(0.1µF)* located near the top left of the board between J1 and R55.
- **C40**	*(4.7µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the left edge of the board.  Located near the left center of the board between C39 and U6.
- **D33**	*(LED Green)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the short lead of the LED.  Located near the top left of the board between R57 and R59.
- **D34**	*(LED Green)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the short lead of the LED.  Located near the top left of the board between R58 and R59.
- **R57**	*(470 ohm)* located near the top left of the board above D33.
- **R58**	*(470 ohm)* located near the top left of the board above D34.
- **R79**	*(22 ohm or Ferrite Bead)* located near the top left of the board between J1 and U6.

- Install either **J1**	*(USB-B)* or **J2** *(USB-B Micro)* but **NOT** both!

Next do either **A** or **B** but **NOT** both!  To be clear, **either** install the digital isolator **or** bypass the optocoupler circuits, but do not do both.

**A) To install an Analog Devices ADUMx201 or Texas Instruments ISO7421 digital isolator:**
- **U9**	*(ADUMx201/ISO7421)* located to the right of the U1. Pin 1 on the device goes to Pin 1 on the PCB.
- **Jumper**	*(Jumper Wire)* between pin 1 of U9 to R60 pad directly across from U9 pin 1.
- **Jumper**	*(Jumper Wire)* between pin 2 of U9 to R60 pad closest to C44.
- **Jumper**	*(Jumper Wire)* between pin 4 of U9 to either pad between C44 and C4.
- **Jumper**	*(Jumper Wire)* between pin 7 of U9 to the RXB pad.
- **Jumper**	*(Jumper Wire)* between pin 8 of U9 to R56 pad closest to C39.


**B) To bypass the optocoupler circuits:**
- Install a jumper wire from **RX** (one of the R60 pads) to **RXB** (near C21).  This bypasses the optocoupler circuit.
- Install a jumper wire from **TX** (near R60) to **TXB** (near C40).  This bypasses the optocoupler circuit.

If you have the **original** FreeEMS serial monitor program (included with the freeems-vanilla firmware) you will need the PNP transistor modification shown here, **HOWEVER** if you have the modified "**seank.hackers.special.by.fred.s19**" serial monitor program you **DO NOT** need the PNP modification:

Install the PNP transistor modification to allow the MCU to operate without the USB cable being plugged in and connected to a computer:
- **Jumper**	*(Jumper Wire)* between U9 pin 5 to U8 pin 5.
- **PNP**	*(2N3906)* Connect Emitter to R60 pad directly across from U9 Pin 1, connect Collector to U8 pin 6, connect Base to R56 pad closest to C39.

