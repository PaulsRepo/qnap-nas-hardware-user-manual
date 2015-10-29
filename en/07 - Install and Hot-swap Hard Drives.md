# 07.	Install and Hot-swap Hard Drives



 Caution:
	Before starting, please ensure that you turn off the NAS, disconnect the 

power adaptor, network cable(s), and also remove any other device/cable that is 

attached to the NAS. 
	Please ensure that you wear an antistatic wrist strap during the entire 

process to prevent electrostatic discharge. The crocodile clip should be connected 

to the ground. 


## 7.1	Install Hard Drives



Follow the below steps to install hard drives on the NAS.


### 7.1.1.	TS-453Mini



1.	Remove the case cover. Open and remove the hard drive tray.
 

2.	Install the HDD:
a.	For 3.5” HDDs, remove both brackets (pinch the end marked “pull” to pull and 

separate the bracket) from the tray. Place the hard drive on the tray and clip-in 

both brackets.
 
 

b.	For 2.5” HDDs/SSDs, only remove the bracket next to the 2.5” screw holes 

(they are marked on the bottom of the tray.) Secure the three screws in the back of 

the hard drive tray.
 

3.	Insert the hard drive tray into the Turbo NAS all the way to the bottom and 

close the case cover.
 


### 7.1.2.	TS-112P, TS-212P and TS-251C



1.	Loosen the screws on the rear (top and bottom) of the NAS. Remove the case 

cover of the NAS by sliding it apart (see the underside of the NAS for visual 

indicators of the NAS case being locked/unlocked.) 
 
 
2.	Install the hard drives:
a.	For TS-112P: Place the hard drive in the hard drive cradle and slide it 

forward to lock it into the connector. Secure the screws on the slides of the hard 

drive. 
 

b.	For TS-212P and TS-251C: Place the first hard drive in the hard drive cradle 

and slide it forward to look it into the connector. Place the second hard drive on 

top of the first hard drive and secure the screws on the slides of both hard drives. 

Connect the SATA cable and power cable to the connectors as shown in the picture.
 
 

3.	After installing the hard drives, cover the NAS with the casecover and 

fasten the round head screws. Then, place the NAS vertically on the stands. 
 


### 7.1.3.	TAS-168, TAS-268



1.	Remove the toolless screw and top cover.  
 

2.	Put the hard drive in the hard drive cradle and slide it forwards to lock it 

into the SATA connector. Clip in both brackets, slide the bracket into the hole in 

point 2 before pressing the bracket towards the HDD (for the TAS-268, repeat the 

same step for the second drive.)
 

3.	Align point a on the case cover with point b on the front of the NAS (see 

figure below). Push forward the case cover (step 2) and fasten the toolless screw to 

secure the case cover. 
 


### 7.1.4.	IS-453S



1.	Remove all four screws from the front panel. 
 

2.	Remove the drive tray.  
 

3.	Attach the drive to the tray and secure the four screws in the back of the 

drive tray.
 

4.	Insert the drive tray into the NAS all the way to the end. 
 

5.	Repeat Step 2 to 4 to install the remaining drives. Please follow the HDD 

Sequence shown in Step 2 to do so. 


6.	Close the front panel and fasten the screws.

## 7.2	Hard-swap Hard Drives

The QNAP NAS is compatible with 2.5-inch/3.5-inch SATA hard disk drives from major 

hard disk brands. For the updated hard drive compatibility list, please visit 

http://www.qnap.com.

 Caution:
	QNAP disclaims any responsibility for product damage/malfunction or data 

loss/recovery due to misuse or improper installation of hard disks in any occasions 

for any reasons.
	Note that if a hard drive (new or used) which has never been installed on 

the NAS beforeit is installed, the hard drive will be formatted and partitioned 

automatically and all the disk data will be cleared.

System	Supports 3.5-inch SATA Hard Drives	Supports 2.5-inch SATA Hard Drives	

Supports SSD	Supports Hot-swapping Hard Drives (RAID 1 or above only)
TS-112P, TS-212P, TS-251C	✔			
TAS-168, TAS-268	✔			✔(TAS-268)
HS-210, HS-251, HS-251+,TS-131, TS-231,TS-231+, TS-251,TS-251+, TS-431, TS-431+, 

TS-431U,TS-451, TS-451+, TS-651, TS-851, TS-253 Pro, TS-453 Pro, TS-453S Pro,TS-563, 

TS-653 Pro, TS-853 Pro,TS-853S Pro, TS-879 Pro, TS-1079 Pro, TS-879U-RP, TS-1279U-

RP, TS-EC879U-RP, TS-EC1279U-RP, TS-1679U-RP, TS-EC1679U-RP, TS-451U, TS-453U, TS-

453U-RP, TS-853U, TS-853U-RP, TS-1253U, TS-1253U-RP, TS-870U-RP, TS-1270U-RP, TS-

470/470 Pro, TS-670/670 Pro, TS-870/870 Pro, TVS-463, TVS-663, TVS-863, TVS-863+, 

TS-453minI, TS-463U, TS-463U-RP, TS-863U, TS-863U-RP, TS-1263U, TS-1263U-RP	✔	

✔	✔	✔
TS-451S, TS-453S Pro, TS-853S Pro, IS-453S		✔	✔	✔

 
The NAS supports hot-swapping the hard drives when 1 member drive crashes in RAID 1, 

1–2 member drives crash in RAID 5 or RAID 6. Follow the steps below to hot-swap the 

hard drive when a member drive fails in a RAID configuration.
1.	Login the NAS and check the disk volume configuration in “Volume 

Management”.
2.	The volume status should be “in degraded mode”.
3.	Prepare a new hard drive to replace the failed one. The capacity of the new 

hard drive should be the same as or larger than the failed hard drive.
4.	Unplug the failed drive from the NAS. Wait for about 20 seconds or until the 

server beeps twice.
5.	Remove the failed drive from the drive tray.
6.	Install the new hard drive on the drive tray. Insert it to the NAS.
7.	The server should beep 1.5 seconds twice.
8.	Check the volume status on the web administration page. The volume should be 

rebuilding.

 Warning: Users are strongly recommended to turn OFF the server before replacing the 

hard drive to reduce the risk of electric shock.