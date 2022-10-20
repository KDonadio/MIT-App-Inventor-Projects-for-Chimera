
The zip file contains the MPLABX v6.00 project for the Chimera Curiosity Board.
This code does not implement the que system that Frank has worked on. 
The HEX file is also included should you prefer to program the board directly.

The main code is in app_trsps_handler.c, myapp.c and app_ble_handler.
**app_trsps_handler.c** I have included some defines for the LED's and parse the BLE received data here.
**myapp.c** I tried to keep as much code in one place as possible so much of the code is here.
**app_ble_handler.c** In this file around line 92 I re-enable BLE advertisements upon a disconnect event. 



