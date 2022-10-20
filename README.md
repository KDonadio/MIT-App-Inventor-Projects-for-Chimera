# MIT-App-Inventor-Projects-for-Chimera

There are several projects here which were created using MIT App Inventor. 

Chimera Scan Direct RGB:  allows you to either scan for BLE devices using a list to select the device or directly connect using the MAC address. This App allows you to control the RGB LED on the Chimera Curiosity Board.

MCHP Chimera:  a similar App that has a much nicer look but as you will see this nice look is not easy in MIT App Inventor. This App allows RGB LED control, user switch status, temerature status and PWM control.

Text2Speech:  a neat App that is not BLE enabled but shows some neat features. With this App you push a button and say "LED red" and the indicator will turn red. Push a button for the temperature and it will be spoken to you. Can you add these features to your MIT App Inventor projects for Chimera?

Recently there has been an issue with Android 12 OS as it uses different permissions than prior versions. This renders the current BLE extension broken - but I have a work around. It actually checks for Android 12 and sets the permissions.
This works for now but Evan at MIT told me they will be releasing a new BE extension very soon to take care of this issue. To use the work around another extension is used - GetApiLevel.

