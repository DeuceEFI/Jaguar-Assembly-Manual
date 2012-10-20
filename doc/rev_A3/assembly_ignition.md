#### Ignition circuits
**Step 24 :**
/-- 337x260 img/ignition.png "Install ignition XOR components" --/

- **R14**	*(1k ohm)* located upper right between R22 and R64. 
- **R64**	*(1k ohm)* located upper right between R14 and BDM.
- **R65**	*(1k ohm)* located upper right to the right of U5.
- **R15**	*(470 ohm)* located upper right to the right of U5 and above R65.
- **JP1**	*(3 pin 0.100" header strip)* for selecting inverted or non-inverted input.
- **JP2**	*(3 pin 0.100" header strip)* for selecting inverted or non-inverted output.
- **JP7**	*(wire jumper)*  Install a wire jumper between these pads for normal operation.
- **JP8**	*(wire jumper)*  Install a wire jumper between these pads for normal operation.
- **U5**	*(CD74AC86E XOR Gate)*

JP7 and JP8 are there if someone wants to use MCU pins other than Port T0 (JP7) and Port T1 (JP8) with the XOR I/O circuits or to use another output circuit.

The exclusive-OR gate specified in the Bill of Materials is ONLY to be used as logic level outputs to the logic level inputs on EDIS/DIS modules! 
