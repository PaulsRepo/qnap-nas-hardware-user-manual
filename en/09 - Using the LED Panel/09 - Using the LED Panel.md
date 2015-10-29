
# 09.	Using the LCD Panel



This feature is only provided by the NAS models with LCD panels.Please visit 

http://www.qnap.com for details.

The NAS provides a handy LCD panel for users to perform disk configuration and view 

the system information.

When the NAS has started up, the server name and IP address will be shown.
N	A	S	5	F	4	D	E	3			

				
1	6	9	.	2	5	4	.	1	0	0	

.	1	0	0	

For the first time installation, the LCD panel shows the number of hard drives 

detected and the IP address. Configure the hard drives.
Number of hard drives detected	Default disk configuration	Available disk 

configuration options*
1	Single	Single
2	RAID 1	Single -> JBOD ->RAID 0 -> RAID 1
3	RAID 5	Single -> JBOD -> RAID 0 -> RAID 5
4 or above	RAID 5	Single ->JBOD -> RAID 0 -> RAID 5 
 ->RAID 6
*Press the “Select” button to choose the option, and press the “Enter” button to 

confirm.

For example, when 5 hard drives installed are available on the NAS, the LCD panel 

shows:
C	o	n	f	i	g	.		D	i	s	

k	s	?		
→	R	A	I	D	5						

				

Press the “Select” button to browse more options, for example, RAID 6.
Press the “Enter” button and the following message shows. Press the “Select” button 

to select “Yes” to confirm.
C	h	o	o	s	e		R	A	I	D	

5	?			
→	Y	e	s			N	o				

				

 
When RAID 1, RAID 5, or RAID 6 configuration is executed, the system will initialize 

the hard drives, create the RAID device, format the RAID device, and mount it as a 

volume on the NAS. The progress will be shown on the LCD panel. When it reaches 

100%, the RAID volume can be accessed. Users can create share folders and upload 

files to the folders on the NAS. In the meantime, to make sure the stripes and 

blocks in all the RAID component devices are ready, the NAS will execute RAID 

synchronization and the progress will be shown on “Disk Management” > “Volume 

Management” page. The synchronization rate is around 30–60 MB/s (vary by hard drive 

models, system resource usage, etc.)

Note: If a member drive of the RAID configuration was lost during the 

synchronization, the RAID device will enter degraded mode. The volume data is still 

accessible. If a new member drive is added, the NAS will start to rebuild. The 

status can be checked on the “Volume Management” page. 

To encrypt the disk volume*, select “Yes” when the LCD panel shows <Encrypt Volume?

>.The default encryption password is “admin”. To change the password, please login 

the web-based administration interface as an administrator and change the settings 

in “Device Configuration” > “Disk volume Encryption Management”.
E	n	c	r	y	p	t		V	o	l	

u	m	e	?	
→	Y	e	s			N	o				

				

When the configuration is finished, the server name and IP address will be shown. If 

the NAS fails to create the disk volume, the following message will be shown.
C	r	e	a	t	i	n	g	.	.	.	

				
R	A	I	D	5		F	a	i	l	e	

d				

Note: The data encryption functions may not be available in accordance to the 

legislative restrictions of some countries.
 
View system information by the LCD panel
When the LCD panel shows the server name and IP address, press the “Enter” button to 

enter the Main Menu. The Main Menu consists of the following items:
1. TCP/IP
2. Physical disk
3. Volume
4. System
5. Shut down
6. Reboot
7. Password
8. Back

1.	TCP/IP
The following options are available:
	LAN1 IP Address
	LAN1 Subnet Mask
	LAN1 Gateway
	LAN 1 PRI. DNS
	LAN 1 SEC. DNS
	Enter Network Settings
	Network Settings – DHCP
	Network Settings – Static IP*
	Network Settings – BACK
	Back to Main Menu
* In Network Settings – Static IP, users can configure the IP address, subnet mask, 

gateway, and DNS of LAN 1 and LAN 2.

2.	Physical disk
The following options are available:
	Disk Info
	Back to Main Menu

The disk info shows the temperature and the capacity of the hard drive.
D	i	s	k	:	1		T	e	m	p	

:	5	0	°	C
S	i	z	e	:		2	3	2		G	

B				

 
3.	Volume
This section shows the disk configuration of the NAS. The first line shows the RAID 

configuration and storage capacity; the second line shows the member drive number of 

the configuration.
R	A	I	D	5							

7	5	0	G	B
D	r	i	v	e		1	2	3	4		

				

If there is more than one volume, press the “Select” button to view the information. 

The following table shows the description of the LCD messages for RAID 5 

configuration.
LCD Display	Drive configuration
RAID5+S	RAID5+spare
RAID5 (D)	RAID 5 degraded mode
RAID 5 (B)	RAID 5 rebuilding
RAID 5 (S)	RAID 5 re-synchronizing
RAID 5 (U)	RAID 5 is unmounted
RAID 5 (X)	RAID 5 non-activated

4.	System
This section shows the system temperature and the rotation speed of the system fan.
C	P	U		T	e	m	p	:		5	

0	°	C		
S	y	s		T	e	m	p	:		5	

5	°	C		

S	y	s		F	a	n	:	8	6	5	

R	P	M		
											

				

5.	Shut down
Use this option to turn off the NAS. Press the “Select” button to select “Yes”.Then 

press the “Enter” button to confirm.

6.	Reboot
Use this option to restart the NAS. Press the “Select” button to select “Yes”. Then 

press the “Enter” button to confirm.
 
7.	Password
The default password of the LCD panel is blank. Enter this option to change the 

password of the LCD panel. Select “Yes” to continue.
C	h	a	n	g	e		P	a	s	s	

w	o	r	d	
					Y	e	s		→	N	

o				

Enter a password of maximum 8 numeric characters (0-9). When the cursor moves to 

“OK”, press the “Enter” button. Verify the password to confirm the changes.
N	e	w		P	a	s	s	w	o	r	

d	:			
											

			O	K

8.	Back
Select this option to return to the main menu.

System Messages
When the NAS encounters system error, an error message will be shown on the LCD 

panel. Press the “Enter” button to view the message. Press the “Enter” button again 

to view the next message.
S	y	s	t	e	m		E	r	r	o	

r	!			
P	l	s	.		C	h	e	c	k		

L	o	g	s	

System Message	Description
Sys. Fan Failed	The system fan fails
Sys. Overheat	The system overheats
HDD Overheat	The hard drive overheats
CPU Overheat	The CPU overheats
Network Lost	Both LAN 1 and LAN 2 are disconnected in failover or load-balancing 

mode
LAN1 Lost	LAN 1 is disconnected
LAN2 Lost	LAN 2 is disconnected
HDD Failure	The hard drive fails
Vol1 Full	The volume is full
HDD Ejected	The hard drive is ejected
Vol1 Degraded	The volume is in degraded mode
Vol1 Unmounted	The volume is unmounted
Vol1 Nonactivate	The volume is not activated
