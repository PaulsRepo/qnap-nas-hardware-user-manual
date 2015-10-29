# LED and Alarm Buzzer Specifications

The LED indicators of the NAS indicate the system status and information. When the 

NAS is turned on, check the following items to make sure the system status is 

normal. Note that the following LED information is applicable only when users have 

properly installed the hard drive, and connected the NAS to the network and the 

power supply.
LED	Color	LED Status	Description
System Status	Red/
Green	Flashes green and red alternately every 0.5 sec
1.	The hard drive on the NAS is being formatted.
2.	The NAS is being initialized.
3.	The system firmware is being updated.
4.	RAID rebuilding is in process.
5.	Online RAID Capacity Expansion is in process.
6.	Online RAID Level Migration is in process.
		Red	1.	The hard drive is invalid.
2.	The disk volume has reached its full capacity.
3.	The disk volume is going to be full.
4.	The system fan is out of function.
5.	An error occurs when accessing (read/write) the disk data.
6.	A bad sector is detected on the hard drive.
7.	The NAS is in degraded read-only mode (2 member drives fail in a RAID 5 or 

RAID 6 configuration, the disk data can still be read).
8.	Hardware self-test error.
		Flashes red every 0.5 sec 	The NAS is in degraded mode (one 

member drive fails in RAID 1, RAID 5 or RAID 6 configuration).
		Flashes green every 0.5 sec	1.	The NAS is starting up.
2.	The NAS is not configured.
3.	A hard disk drive is not formatted.
		Flashes green every 2 seconds	The NAS is in S3 sleep mode .
		Green	The NAS is ready.
		Off	All the hard disk drives on the NAS are in standby mode.
LAN	Orange	Orange	The disk data is being accessed from the network and a 

read/write error occurs during the process.
		Flashes orange	The NAS is being accessed from the network.
10GbE 	Green	Green	The 10GbE network expansion card is installed.
		Off	No 10GbE network expansion card is installed.
HDD3
Red/ Green	Flashes red	The disk data is being accessed and a read/write 

error occurs during the process.
		Red	A hard disk drive read/write error occurs.
		Flashes green	The disk data is being accessed.
		Green	The hard disk drive can be accessed.
USB3
Blue	Flashes blue every 0.5 sec	1.	A USB device (connected to the front 

USB port) is being detected.
2.	A USB device (connected to the front USB port) is being removed from the 

NAS.
3.	The USB device (connected to the front USB port of the NAS) is being 

accessed.
4.	The data is being copied to or from the external USB or eSATA device.
		Blue	A front USB device is detected (after the device is 

mounted).
		Off	1.	No USB device is detected.
2.	The NAS has finished copying the data to or from the USB device connected to 

the front USB port.
eSATA 	Orange	Flashes	The eSATA device is being accessed.
		Off	No eSATA device can be detected.

 
Beep alarm (for all NAS models)

The beep alarm can be disabled in “System Administration” > “Hardware Settings”.
Beep sound	Number of Times	Description
Short beep (0.5 sec)
1.	The NAS is starting up.
2.	The NAS is being shut down (software shutdown).
3.	The user presses the reset button to reset the NAS.
4.	The system firmware has been updated.
Short beep (0.5 sec)	3	The user tries to copy the NAS data to the external 

storage device from the front USB port, but the data cannot be copied.
Long beep (1.5 sec)	3, every 5 min	The system fan is out of function.
Long beep (1.5 sec)	2	1.	The disk volume is going to be full.
2.	The disk volume has reached its full capacity.
3.	The hard drives on the NAS are in degraded mode.
4.	The user starts the hard drive rebuilding process.
5.	A hard drive is plugged in or out.
	1	1.	The NAS is turned off by force shutdown (hardware shutdown).
2.	The NAS has been turned on successfully and is ready.

