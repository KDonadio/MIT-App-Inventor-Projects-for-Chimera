
The zip file contains the MPLABX v6.00 project for the Chimera Curiosity Board.
This code does not implement the que system that Frank has worked on. 
The HEX file is also included should you prefer to program the board directly.

The main code changes are in app_trsps_handler.c, myapp.c and app_ble_handler.<br><br>
**app_trsps_handler.c** <br>
  I have included some defines for the LED's and parse the BLE received data here. <br><br>
**myapp.c** <br>
  I tried to keep as much code in one place as possible so much of the code is here. <br><br>
**app_ble_handler.c** <br> 
  In this file around line 92 I re-enable BLE advertisements upon a disconnect event. <br>



