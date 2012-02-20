# Testing Inputs

It's important that you verify the correct operation of your input conditioning circuits before attempting to use the device on a vehicle.

## Test BRV Input

 - Connect a 5v DC supply to the pad labeled **BRV-12v**
 - Connect the negative lead from the 5v DC supply to the pad labeled **GND**
 - Open MTX, you should see 5v DC registered for BRV
 - Connect a 12v DC supply to the pad labeled **BRV-12v**
 - Connect the negative lead from the 12v DC supply to the pad labeled **GND**
 - Open MTX, you should see 12v DC registered for BRV


## Testing analog sensor inputs
 
 - Attach a variable voltage source, such as a JimStim, to one of the Jaguar analog sensor inputs.
 - Adjust the simulated sensor and observe the corresponding values changing within MTX.
 - Repeat the process for all analog sensor inputs being used.
	- If there is no change seen within MTX check the following:
		- That you have the correct corresponding analog input.
		- The analog sensor input circuit is correctly assembled. 


## Testing RPM inputs

 - *Attach an RPM signal source such as a JimStim*
 - *Load appropriate code for that signal type.*

### Logic Analyser (LA) RPM check
/-- 337x260 img/operation/ovl_rpm_la.png "" Logic analyser log trace review
 
Test procedure:
 - Load the Listener.s19 firmware to your Jaguar board MCU.
 - Take a LA type log maintaining a RPM below 2k.
 - Review the .LA log with OLV and confirm that **T0** it is clean, with no randomness (should look similar to the RPM LA LOG left).

*note: future versions of OLV will be able to view LA logs. Please use an old version (hash 16e284fe56392a033f9aaee7ba3cf2958731c54e) of OLV to view LA logs at this time.*
--/

### Full RPM range check
/-- 337x260 img/operation/olv_rpm_fullbin.png "Review of RPM logging"

Test procedure:
 - Load the appropriate firmware for rpm test, the *HallOrOptical-Distributor-4of64.s19* is a good option.
 - Take a standard binary (.bin) log while varying the rate of your signal
 - Review the .bin log with OLV and confirm that the reported **RPM** variable is smooth and matches your expectations. (Shown left)
--/

*You are now ready to test your physical outputs using the Bench Test decoder.*

