## Over-Voltage Protection

Turn the Jaguar version 0.6-alpha PCB over and orient the board so that the U12 (TC442xA) silk screen is located in the upper left corner.  You should see all of the SMD components, they should be on the this side of the board.

#### Install Over-Voltage Protection components
**Step 11 :** 
/-- 337x260 img/mcu_power_supply.png "Install Over-Voltage Protection components" --/

 1. **Ux** *(xxx)* Install this component on the SMD side with the dual pins facing the top of the board.
 2. **Rxx** *(xxx ohm)* 
 3. **Rxx** *(xxx ohm)* 
 4. **Rxx** *(xxx ohm)* 
 5. **Rxx** *(xxx ohm)*
 6. **Q12** *(xxx)* Install this component on the SMD side with the xxx pins facing the xxx of the board.
 7. **F1** *(xxx)*


####Test Over-Voltage Protection components
**Step 12 :**
/-- 337x260 img/mcu_power_supply.png "Test Over-Voltage Protection components" --/

 1. Connect 12v supply positive (+) to the pad labeled **12v-SW** between D44 and U6.
 2. Connect 12v supply negative (-) to the pad labeled **GND** between D3 an R55.
 3. Set your DMM to measure 20v DC.
 4. Connect the negative (-) lead from your **first** DMM to the ground lead from your 12v supply.
 5. Connect the positive (+) lead from your **first** DMM to the round pad labeled **5v** in the **MAP** section.
 6. Connect the negative (-) lead from your **second** DMM to the ground lead from your 12v supply.
 7. Connect the positive (+) lead from your **second** DMM to the round pad labeled **TPS-5v** near the bottom right section of the board.
 8. Both of your DMMs should read +5v DC (+/- 0.10v), if it does then check to make sure that Q12 or the Analog-5v regulator **U2** is not overheating. 
 9. Next the connect the **TPS-5v** pad to a 12v power supply and ensure that your **first** DMM does not read over 5.25v.  Also note if Q12 overheats.
10. Turn off the 12v supply and disconnect your leads.


