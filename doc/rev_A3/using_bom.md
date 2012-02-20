# Bill of Materials

The BOM is broken down by component type and for those components that have multiple values you, as the end user, can pick and choose which components are best suited to your project. For each sub-circuit there is a matching assembly section.

Completing all of these steps are compulsory to achieve a functional 'FreeEMS microcontroller'. 

Open the BOM, it is found in the **docs** directory and is called **Jaguar.ods**.

### Overview with Important notes

- Only install one USB connector (either the USB-B **or** USB-B-mini but **NOT** both).

#### Legend of acronyms ####
Some of these acronyms are used in the schematic documentation.

- **AAP**: *(**A**tmospheric **A**bsloute **P**ressure)* 
  	- Used for normalisation of the MAP vs atmospheric pressure, this is considered optional. Choose this if you live in a mountainous area, or intend to visit such areas using your vehicle.  Currently this is not supported on the Jaguar Revision A3 board, but may have a pad to connect the supporting circuitry to in a future revision.

- **BDM**: *(**B**ackground **D**ebug **M**odule)*
	- Used to program the Serial Monitor and for additional troubleshooting.

- **CHT**: *(**C*oolant **H**ead **T**emperature)*
	- Sensor used to measure engine coolant temperature in the water jacket.

- **DIS**: *(**D**istributorless **I**gnition **S**ystem)*
	- A method of wasted spark ignition implemented on General Motors vehicles.

- **GND**: *(**G**ro**nd**)*

- **IAT**: *(**I**ntake **A**ir **T**emperature)*
	- Sensor used to measure outside air temperature, usually found in the air cleaner.
	
- **IGN**: *(**Ign**ition)*
 
- **INJ**: *(**Inj**ector)*

- **MAF**: *(**M**ass **A**ir **F**low)* 
	- This is an alternative to the MAP sensor that is unsupported at this time, however the circuit is cheap and can be used as a general purpose analog input also.
 
- **MAP**: *(**M**anifold **A**bsolute **P**ressure)* 
	- The BOM is tailored to a normally aspirated vehicle with the preferred sensor (MPX4100AP) and provides sufficient accuracy for all naturally aspirated vehicles.  If you are going to use the Jaguar on a boosted vehicle then you should use a MPX4250AP which has sufficient range to cover boosted applications up to 21psi. If you are planning boost levels in excess of or close to 21psi, from a relatively large turbo, there are other options that you need to investigate.

- **O2**: *(**O**xygen)*
  	- Only linear wide-band lambda sensors are supported at this time by the freeems-vanilla firmware.

- **RPM**: *(**R**evolutions **P**er **M**inute)*

- **TPS**: *(**T**hrottle **P**osition **S**ensor)*

- **USB**: *(**U**niversal **S**erial **B**us)*

### BOM Configuration Overview

*Git users download the [BOM here].*

