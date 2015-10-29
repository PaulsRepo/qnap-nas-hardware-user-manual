
# RAID Recovery



The QNAP NAS supports exclusive RAID recovery technology to recover a failed RAID 

disk volume from unintentional disconnection or removal of the hard drives from the 

system. Using the RAID recovery, users can recover an inactive RAID 1, RAID 5,or 

RAID 6 volume to degraded mode, or an inactive RAID 0 and JBOD configuration to 

normal.
Disk volume	Supports RAID recovery	Maximum number of disk removal allowed
Single 	No	-
JBOD	Yes	1 or more
RAID 0	Yes	1 or more
RAID 1	Yes	1 or 2
RAID 5	Yes	2 or more
RAID 6	Yes	3 or more
RAID 10	No	-

If the volume status is not active, users can install the same hard drives back to 

the same slots of the NAS. Then click “RECOVER” on the “Disk Management” > “Volume 

Management” page. Wait for about 60 seconds for the process to complete. When 

finished, the data can be accessed.

Note:
	After recovering a RAID 1,RAID 5, or RAID 6 disk volume from not active to 

degraded mode by the RAID recovery, users can read or write the volume normally. The 

volume status will be recovered to normal after synchronization.
	If the disconnected drive member is damaged, the RAID recovery function will 

not work.

 
	Standard RAID 5	QNAP RAID 5	Standard RAID 6	QNAP RAID 6
Degraded mode	N-1	N-1	N-1 & N-2	N-1 & N-2
Read only protection (for immediate data backup &hard drive replacement)	N/A	

N-1, bad blocks found in the surviving drives of the array.	N/A	N-2, bad 

blocks found in the surviving drives of the array.
RAID recovery
(RAID status: Not active)	N/A	If re-inserting all the original hard disk 

drives to the NAS and they can be spun up, identified, accessed, and the hard drive 

superblock is not damaged.	N/A	If re-inserting all the original hard disk 

drives to the NAS and they can be spun up, identified, accessed, and the hard drive 

superblock is not damaged).
RAID crash 	N-2	N-2 failed hard drive and any of the remaining hard drives 

cannot be spun up or identified or accessed.	N-3	N-3 and any of the remaining 

hard drives cannot be spun up or identified or accessed.
N = Number of hard disk drives in the array