# MIT-App-Inventor-Projects-for-Chimera

There are several projects here which were created using MIT App Inventor. 

**Chimera Scan Direct RGB**  
>This App allows you to either scan for BLE devices using a list to select the device or directly connect using the MAC address. 
>The main feature of this App is controlling the RGB LED on the Chimera Curiosity Board.
***
**MCHP Chimera**  
>This App is similar but has a much nicer look. Looking at the components used in the Design window you will see this nice look is not easy to accomplish in MIT >App Inventor. 
>This App allows RGB LED control with slide switches, a user switch status, temperature status and PWM control.
***
**Chimera QR Direct RGB**
>This App is the same as Chimera Scan Direct RGB but adds a QR scanner to get the MAC address. When you click on the "Scan" button it opens your camera on your >phone. Scan the QR code of the BLE module, which is the MAC address, and it can do a direct connect with it.
***
**Text2Speech**  
>This is a neat App that is not BLE enabled but shows some neat features. With this App you push a button and say "LED red" and the indicator will turn red. >Push a button for the temperature and it will be spoken to you. Perhaps you could add these features to your MIT App Inventor projects for Chimera?
<br>
<br>
Recently there has been an issue with Android 12 OS as it uses different permissions than prior versions. This renders the current BLE extension broken - but I have a work around. It actually checks for Android 12 and sets the permissions.
This works for now but Evan at MIT told me they will be releasing a new BLE extension very soon to take care of this issue. To use the work around another extension is used - GetApiLevel.

