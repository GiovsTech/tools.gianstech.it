---
title: 'Application Behavior'
date: 2019-02-11T19:27:37+10:00
weight: 5
---

When you start LinuxEFIMounter, you are welcomed by a simple introduction window.

![](https://i.imgur.com/MVIIvqr.png)

To skip it, just press any key.

![](https://i.imgur.com/YvtsXMy.png)

After it, you get brought to the main menu.
Right after you start the program, you are able to do two things:

- Choose a partition to mount
- Upgrade the script
- Quit the program

To choose the action to perform, just type `1` (to mount a partition), `U` (to upgade LinuxEFIMounter) or `E` (to exit LinuxEFIMounter) and then hit Enter.

If you type `U`, the program will show the **Upgrade Menu** and will check the availability of new updates. 

![](https://i.imgur.com/qSQRdi6.png)
This screen shows that the program is up to date.

![](https://i.imgur.com/xMKxkqd.png)
If a new update is found, the program will install it.

![](https://i.imgur.com/2GHg3hC.png)
And here you have your success screen. You have to run the script again to apply the update.

When you want to mount a partition, you have to press `1` at the main menu. 

![](https://i.imgur.com/7aiXtmK.png)

![](https://i.imgur.com/GqviTRO.png)

You'll get to the point where you need to select the partition to mount.

First, locate in the list the drive you want to mount the EFI partition of, then type its path (/dev/...) followed by the partition number (e.g. "/dev/sda`1`") corresponding to your EFI partition. Then hit Enter.

![](https://i.imgur.com/ShAGM5n.png)

Type `M` to mount the partition. Else, type `B` to go back to the main menu.

![](https://i.imgur.com/9Bcsta6.png)
Congrats! Your EFI Partition is now mounted to "`/mnt/EFIPartition`".
Once the partition is mounted, you get access to the entire set of actions LinuxEFIMounter is capable of doing.
Now, you're able to do three more things:

- Open the EFI partition in a Terminal instance

- Open it in the File Manager

- Unmount the partition
  
  > Perform this action once you're about to exit LinuxEFIMounter.

![](https://i.imgur.com/aqKdLC1.png)

Option `1` will show you this warning message. Anyway, press any key to open a terminal in "`/mnt/EFIPartition`".

![](https://i.imgur.com/Fw3aZm9.png)
Option `2` will show this message. To open a file manager, press any key.

![](https://i.imgur.com/UqD0mdo.png)
Choosing Option `3` in the main menu will result in this screen. Type `U` and press Enter to continue.

> Before unmounting your EFI Partition, make sure you don't have any open file with unsaved work inside of it. Always save your work and close any file that belongs to the EFI partition before unmounting it.

![](https://i.imgur.com/Qvies0Q.png)
And here you have your success screen. Pressing any key will show again the minimalistic version of the main menu (the one we saw earlier yk, just Mount and Exit...).

![image](https://i.imgur.com/Ue4rP6g.png)
Choosing Option `E` from the main menu while your partition is still mounted will take you to this warning screen, which basically reminds you to unmount your EFI partition before you leave LinuxEFIMounter.