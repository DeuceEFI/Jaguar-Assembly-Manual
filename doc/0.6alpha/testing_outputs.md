# Testing Outputs #

It's important that you verify the correct operation of your output driver circuits before attempting to use the device on a vehicle.

## Testing all low side drivers
/-- 337x260 img/operation/driver_test_circuit.png "Low side test setup" --/

Test Equipment:

 - Standard automotive test bulb (with 15 ohm or greater resistance).
 
Test procedure: 

 - Connect the automotive test bulb between the desired driver channel output and the positive (**+**) lead from your power supply.
 - For each, switch it on and off using the firmware and control packets.
 - Observe your lightbulb being switch on and off.

Repeat the process for each low side driver.

## Final step of construction process

Once you have tested all the low side drivers, you will need to place a small amount of High Temperature Silicone on the legs of the upright components to brace them against damage from vibration.  Do not place any silicone near the MAP sensor, it should be mounted to the PCB using nylon screws with locking nylon nuts (be sure not to tighten too tighly or you may damage the MAP sensor).
