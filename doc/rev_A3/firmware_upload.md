## Uploading the firmware ##

/-- 337x260 img/operation/FreeEMS_loader_settings.png "FreeEMS Loader Application"

1. Install [Seans loader].
2. Connect a USB cable between your computer and the Jaguar board.
3. Jumper the load/run header.
4. Turn the power supply to the Jaguar board **on**.
5. Select the device ``/dev/ttyUSB[n]`` in Unix-like operating systems and ``COM[n]`` on Windows. Where 
``[n]`` is the port number e.g.: ``/dev/ttyUSB0`` or ``COM3``
6. Press the "**Connect**" button.
7. Press the "**Load**" button.
8. Choose a recent s19 of the Bench Test firmware variant. 
9. Wait until the erasing and programming phases are done.
10. Press the "**Close/reset**" button.
11. Remove the load/run jumper.
12. Power cycle the Jaguar board.

*The FreeEMS Bench Test firmware should now be installed on your Jaguar board.*

You will use this procedure to load different FreeEMS firmware from this point forward.

--/

/-- 337x260 img/operation/FreeEMS_loader_advanced.png "Communication settings" --/

## Verifying correct operation of the firmware ##

/-- 337x260 img/operation/CuteComDataStreaming.png "CuteCom streaming FreeEMS data logs"

1. Connect CuteCom with the correct settings and hex mode on.
2. Verify that data is streaming past at a high rate.
3. Send the stop data logging (update.block.with.datalog.stream.type.0x00-OFF.bin) packet from the Freeems-vanilla firmware lib directory and ensure that the stream stops.
4. Clear the text area and turn off hex mode.
5. Send the following test packets and record the returned strings;
	- Get firmware version; (request.firmware.version.bin).
	- Get interface version; (request.interface.version.bin).
	- Get decoder version; (request.decoder.name.bin). 
6. Ensure that the strings returned match what you uploaded.
--/
