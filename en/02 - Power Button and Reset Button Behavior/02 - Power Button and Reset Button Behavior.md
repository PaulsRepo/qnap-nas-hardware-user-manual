# Power Button and Reset Button Behavior

*  Power button: Press to turn on or turn off.
*  System	Power button (Turn on)
*  Power button (Hardware turn off)
*  Power button (Force turn off)

 All models	 Press once	1.5 sec	5 sec

 Reset button: Press to reset the system settings.
 System	Basic system reset 
 (1 beep)	Advanced system reset 
 (2 beeps)
 All models	3 sec	10 sec


## Basic system reset (3 sec)


 Press the reset button for 3 seconds, a beep sound will be heard. The following settings are reset to default:
* System administration password: admin
* TCP/IP configuration: Obtain IP address settings automatically via DHCP
* TCP/IP configuration: Disable Jumbo Frame
* TCP/IP configuration: If port trunking is enabled (dual LAN models only), the port trunking mode will be reset to “Active Backup (Failover)”.
* System Port: 8080 (system service port)
* Security Level: Low (Allow all connections)
* LCD panel password: (blank)
* VLAN will be disabled

*This feature is only provided by the NAS models with LCD panels. Please visit [http://www.qnap.com](http://www.qnap.com) for details.


## Advanced system reset (10 sec)
Press the reset button for 10 seconds; you will hear two beeps at the third and the tenth seconds. The NAS will reset all the system settings to default as it does by web-based system reset in “Administration” > “Restore to Factory Default” except all the data are reserved. The settings such as the users, user groups, and the network share folders previously created will be cleared. To retrieve the old data after the advanced system reset, create the same network share folders on the NAS and the data will be accessible again.


