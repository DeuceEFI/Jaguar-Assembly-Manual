## Power Supplies

Orient the Jaguar Revision A3 board so that the U6 (MPX4100AP) silk screen is located to the left side and U3 will be in the upper left corner.  You should not see any of the SMD components, they should be on the back side of the board.  For the remainder of the assembly manual this will be how the Jaguar board should be oriented to install the through hole components.

#### Install MCU Power Supply components
**Step 7 :** 
/-- 337x260 img/mcu_power_supply.png "Install MCU power supply components" --/

 1. **U3** *(LM2937ET-5.0)* Install this component from the Through Hole side with the heatsink facing away from the center of the board.
 2. **C15** *(0.1µF)* 
 3. **C17** *(0.1µF)* 
 4. **C13** *(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the bottom of the board.
 5. **C19** *(47µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the top of the board.
 6. **D3** *(Not Applicable)* This component is NOT required. 
 7. **D44** *(1N5818-TP)* Direction dependant, orient the **K** lead to the top edge of the board. This is indicated by the white line. 



####Test MCU Power Supply
**Step 8 :**
/-- 337x260 img/mcu_power_supply.png "Test MCU power supply" --/

 1. Connect 12v supply positive (+) to the pad labeled **12v-SW** between D44 and U6.
 2. Connect 12v supply negative (-) to the pad labeled **GND** between D3 an R55.
 3. Set your DMM to measure 20v DC.
 4. Connect the negative (-) lead from your DMM to the ground lead from your 12v supply.
 5. Connect the positive (+) lead from your DMM to the square pad at **JP10**, located between D33 and R17.
 6. You should read +5v DC (+/- 0.20v), if it does then the MCU Power Supply has passed this check.
 7. Turn off the 12v supply and disconnect your leads.
 8. If your MCU Power Supply has passed this test you may now jumper **JP10** to supply power to the MCU.


#### Install Analog Sensors Power Supply components
**Step 9 :** 
/-- 337x260 img/analog_power_supply.png "Install Analog Sensors power supply components" --/

 1. **U2** *(LM2937ET-5.0)* Install this component from the Through Hole side with the heatsink facing away from the center of the board.
 2. **C14** *(0.1µF)* 
 3. **C16** *(0.1µF)*
 4. **C12** *(10µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the bottom of the board.
 5. **C18** *(47µF)* Polarised tantalum capacitor; Make sure that it is oriented so that the positive lead is towards the top of the board.
 6. **D43** *(1N5818-TP)* Direction dependant, orient the **K** lead to the bottom edge of the board. This is indicated by the white line. 
 7. **D2** *(1N5919BG)* Direction dependant, orient the **K** lead to the top edge of the board. This is indicated by the white line. 
 8. **MOV1** *(ERZ-V14D220)* 


####Test Analog Sensors Power Supply
**Step 10 :**
/-- 337x260 img/analog_power_supply.png "Test Analog Sensors power supply" --/

 1. Connect 12v supply positive (+) to the pad labeled **12v-SW** between D44 and U6.
 2. Connect 12v supply negative (-) to the pad labeled **GND** between D3 an R55.
 3. Set your DMM to measure 20v DC.
 4. Connect the negative (-) lead from your DMM to the ground lead from your 12v supply.
 5. Connect the positive (+) lead from your DMM to the square pad at **JP9**, located between C18 and D2.
 6. You should read +5v DC (+/- 0.20v), if you do then your Analog Sensors power supply has passed this check.
 7. Turn off the 12v supply and disconnect your leads.
 8. If your Analog Sensors power supply has passed this test you may now jumper **JP9** to supply power to the rest of the board.

