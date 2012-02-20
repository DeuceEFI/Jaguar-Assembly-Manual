##Method ONE : Pre Reflow

Follow the these instructions to install the **MCU**, the **FT232RL**, the **MAX9926UAEE+**, the 3 **VNN7NV0413TR** MOSFETs and depending on how many high impedance (Hi-Z) fuel injectors you need, install that number of **VND7NV04** MOSFETs. You will find the correct component values in the BOM. The topology of the circuits being assembled can be seen in the schematics.

####MCU

**Step 1 :** 
/-- 337x260 img/placeholder_image.png "MCU with solder paste" 

First we will install the MCU, this will be one of the most difficult components for you to place. It will require a steady hand and patience. The MCU is placed first as it requires the most work, following this procedure will ensure no other components are bumped during the process:

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the MCU (**U1**) pins this will be 112 pads in total. Make sure that you **do not** bridge between pads, care here will save you hours later on having to remove the extra solder.
 2. It is recommended that non-conductive thermal paste be placed in the center of the MCU as this will help to dissipate heat to the copper heat pad below. Make sure that thermal paste is not placed all the way out to the MCU edge as it will ooze out when placed, no thermal paste should contact any pins.
 3. Now place the MCU in location noting that the orientation is marked by the silkscreen **1** on the top side of the board. As you are looking at the board where **Jaguar** can be read on the right hand side of the board, pin **1** will be located in the upper right corner of the MCU pads.

*Congratulations the MCU is now mounted*
--/

####Crystal Oscillator Resistor

**Step 2 :** 
/-- 337x260 img/placeholder_image.png "R62" 

Next we will install R62, this will be another of the more difficult components for you to place. It will require a steady hand and patience. Take care placing the chip resistor in the correct location.

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the R62 pins this will be 2 pads in total. 
 2. Now place R62 in location.

*Congratulations the R62 is now mounted*
--/

####USB UART

**Step 3 :** 
/-- 337x260 img/placeholder_image.png "FT232RL" 

Next we will install the USB to Serial UART, this will be another of the more difficult components for you to place. It will require a steady hand and patience. Take care placing the FT232RL as the pin pitch is the same as the MCU.

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the FT232RL (**U7**) pins this will be 28 pads in total. Make sure that you **do not** bridge between pads, care here will save you hours later on having to remove the extra solder.
 2. Now place the FT232RL in location noting that the orientation is marked by the silkscreen **o** on the top side of the board.  As you are looking at the board where **Jaguar** can be read on the right hand side of the board, pin **1** will be located in the lower left corner of the FT232RL pads.

*Congratulations the FT232RL is now mounted*

You may also wish to install the optocouplers (U8 and U9) at this point if you know you are going to use them to isolate the USB port from the MCU communications ports.  They are mounted down and to the left of the FT232RL chip and just to the right of the MCU (U1).

--/

####MAX9926UAEE+

**Step 4 :** 
/-- 337x260 img/placeholder_image.png "MAX9926UAEE+"

Next we will install the MAX9926UAEE+, this will be another of the more difficult components for you to place. It will require a steady hand and patience. Take care placing the MAX9926UAEE+ as the pin pitch is the same as the MCU.

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the MAX9926UAEE+ (**U4**) pins this will be 16 pads in total. Make sure that you **do not** bridge between pads, care here will save you hours later on having to remove the extra solder.
 2. Now place the MAX9926UAEE+ in location noting that the orientation is marked by the silkscreen **o** on the top side of the board.  As you are looking at the board where **Jaguar** can be read on the right hand side of the board, pin **1** will be located in the lower left corner of the MAX9926UAEE+ pads.

*Congratulations the MAX9926UAEE+ is now mounted*
--/

####VNN7NV0413TR

**Step 5 :** 
/-- 337x260 img/placeholder_image.png "VNN7NV0413TR MOSFETs" 

Next we will install the VNN7NV0413TR MOSFETs, this will be the beginning of the easier components for you to place. It will require a steady hand and patience. 

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the VNN7NV0413TR MOSFETs (**Q9, Q10, Q11**) pins this will be 12 pads in total. Make sure that you **do not** bridge between pads, care here will save you hours later on having to remove the extra solder.
 2. Now place the VNN7NV0413TR MOSFETs in location noting that the orientation is marked by the silkscreen on the top side of the board.  As you are looking at the board where **Jaguar** can be read on the right hand side of the board, these will appear to be mounted with their wording upside down.

*Congratulations the output VNN7NV0413TR MOSFETs are now mounted*
--/

####VND7NV04

**Step 6 :** 
/-- 337x260 img/placeholder_image.png "VND7NV04 MOSFETs" 

Next we will install the VND7NV04 MOSFETs, this will be the beginning of the easier components for you to place. It will require a steady hand and patience. Only mount the number of these to match the number of injectors you wish to drive. <br>
**Examples:**<br>
 - for 4 injectors install **Q1, Q2, Q3 and Q4**<br>
 - for 6 injectors install **Q1, Q2, Q3, Q4, Q5, Q6**<br>
 - for 8 injectors install **Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8**

 1. Take the syringe of solder paste and apply a bead to each of the copper pads for the VND7NV04 MOSFET pins from the above list this will be 3 pads per VND7NV04 MOSFET. Make sure that you **do not** bridge between pads, care here will save you hours later on having to remove the extra solder.
 2. Now place the VND7NV04 MOSFETs in location noting that the orientation is marked by the silkscreen on the top side of the board.  As you are looking at the board where **Jaguar** can be read on the right hand side of the board, these will appear to be mounted with their wording reading from bottom to top.

*Congratulations the injector VND7NV04 MOSFETs are now mounted*
--/

