####RPM/Position Inputs
**Step 16 :**
/-- 337x260 img/rpm.png "Install common RPM input components" --/ <br>
*Only perform either the Hall/Opto/Digital* **OR** *the VR Input Sections but not both.*

- **Install Common RPM Components**
	- **C24**	*(1nF)* located top center between R19 and R18. - ONLY IF NEEDED
	- **C25**	*(1nF)* located top center between R16 and R19. - ONLY IF NEEDED
	- **C26**	*(0.1µF)* located top center between C42 and C43.
	- **C42**	*(10nF)* located top center between R19 and C26.
	- **C43**	*(1µF)* located top center between C26 and R18.
	- **R11**	*(10k ohm)* located top center between D4 and R10.
	- **R12**	*(10k ohm)* located top center between R18 and P20.
	- **R17**	*(10k ohm)* located top center between JP10 and R16.
	- **R18**	*(10k ohm)* located top center between C43 and R12.
	- **R9**	*(2.4k ohm)* located top center below D4.  This is optional for diagnostics.
	- **R10**	*(2.4k ohm)* located top center to the right of D5.  This is optional for diagnostics.
	- **D4**	*(Green LED)* Direction dependant, orient the **K** lead to the bottom edge of the board (towards R9). This is indicated by the short lead of the LED.   located top center above R9.   This is optional for diagnostics.
	- **D5**	*(Green LED)* Direction dependant, orient the **K** lead to the top edge of the board (towards R17). This is indicated by the short lead of the LED.   located top center above R11.   This is optional for diagnostics.

**Step 17 :**
- **RPM0 - Hall/Opto/Digital RPM Input **<br>
**Install :**
	- **R22** 	*(1k ohm)*	

**OR**

- **RPM0 - VR Input **<br>
**Install :**
	- **R23** 	*(5k ohm)*	
	- **R19**	*(10k ohm)* located top center between C25 and C24.

**Step 18 :**
- **RPM1 - Hall/Opto/Digital RPM Input **<br>
**Install :**
	- **R21** 	*(1k ohm)*	

**OR**

- **RPM1 - VR Input **<br>
**Install :**
	- **R20** 	*(5k ohm)*
	- **R16**	*(10k ohm)* located top center between R17 and C25.

