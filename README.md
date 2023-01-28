# Appinventor_Debug
Debug and test versions PhyscialoidLibrary, com.SerialOTG.aix, com.Modbus.aix and test programs (Note: can be changed any time).  
 
Physicaloid Library:

Add support for Android12. 

Change USB device selection by VID or VID/PID to a single table

Add VID 1a86, PID 7522 : LD-C100 USB TO CT-62 For Yaesu
 
 
SerialOTG:


Modbus:

Add support for 16bit write and single register read


230126 Ver 1.5 beta is available under Arduino-Debug directory

Uppdated com.SerialOTG.aix, SeraialOTG.aia, SerialOTG.apk

Changes: Compatible with Android12

Default driver CDC if no VID/PID defined in the extension

Possibility to force driver with property/method USBdriver. Must be set before open. See SerialOTG.apk )aia) for list of drivers

Extend timeout for TCP-clien 0.5s->5s for connections over LTE
