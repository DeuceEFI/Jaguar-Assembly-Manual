## Power Supplies

Orient the Jaguar Revision A3 board so that the U6 (MPX4100AP) silk screen is located to the right side and U3 will be in the lower left side.  You should not see any of the SMD components, they should be on the back side of the board.  For the remainder of the assembly manual this will be how the Jaguar board should be oriented to install the through hole components.

#### Install MCU Power Supply components
**Step 7 :** 
/-- 337x260 img/placeholder_image.png "" Install MCU power supply components.

 1. **U3** *(LM2937ET-5.0)* Install this component from the Through Hole side with the heatsink facing away from the center of the board.
 2. **C13** *(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the negative lead is towards the bottom of the board.
 3. **C15** *(0.1µF)* 
 4. **D44** *(1N5818-TP)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the white line. 
 5. **C17** *(0.1µF)*
 6. **C19** *(47µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the negative lead is facing C13.
 7. **D3** *(1N5919BG)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the white line. 
--/

####Test MCU Power Supply
**Step 8 :**
/-- 337x260 img/placeholder_image.png "" Test MCU power supply.

 1. Connect 12v supply positive (+) to the pad labeled **12v-SW** next to D44.
 2. Connect 12v supply negative (-) to the pad labeled **GND** next to D3.
 3. Set your DMM to measure 20v DC.
 4. Connect the negative (-) lead from your DMM to the ground lead from your 12v supply.
 5. Connect the positive (+) lead from your DMM to the square pad at **JP10**.
 6. You should read +5v DC (+/- 0.20v), if it does then the MCU Power Supply has passed this check.
 7. If your MCU Power Supply has passed this test you may now jumper **JP10** to supply power to the MCU.
--/

#### Install Analog Sensors Power Supply components
**Step 9 :** 
/-- 337x260 img/placeholder_image.png "" Install Analog Sensors power supply components.

 1. **U2** *(LM2937ET-5.0)* Install this component from the Through Hole side with the heatsink facing away from the center of the board.
 2. **C12** *(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the negative lead is towards the bottom of the board.
 3. **C14** *(0.1µF)* 
 4. **D43** *(1N5818-TP)* Direction dependant, orient the **K** lead to the top edge of the board. This is indicated by the white line. 
 5. **C16** *(0.1µF)*
 6. **C18** *(47µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the negative lead is facing C12.
 7. **D2** *(1N5919BG)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the white line. 
 8. **MOV1** *(ERZ-V14D220)* 
--/

####Test Analog Sensors Power Supply
**Step 10 :**
/-- 337x260 img/placeholder_image.png "" Test Analog Sensors power supply.

 1. Connect 12v supply positive (+) to the pad labeled **12v-SW** next to D44.
 2. Connect 12v supply negative (-) to the pad labeled **GND** next to D3.
 3. Set your DMM to measure 20v DC.
 4. Connect the negative (-) lead from your DMM to the ground lead from your 12v supply.
 5. Connect the positive (+) lead from your DMM to the square pad at **JP9**.
 6. You should read +5v DC (+/- 0.20v), if you do then your Analog Sensors power supply has passed this check.
 7. If your Analog Sensors power supply has passed this test you may now jumper **JP9** to supply power to the rest of the board.
--/
