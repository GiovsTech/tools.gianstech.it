---
title: 'Usage'
date: 2019-02-11T19:30:08+10:00
draft: false
weight: 4
---

### Supported actions

LinuxEFIMounter is very easy to use. It's got a **simple CLI** with numbers and menus that are really easy to navigate through. 
With LinuxEFIMounter you can:

- Mount an EFI partiton
- Upgrade the script
- Browse its content
  - Via the Command Prompt
  - Via the File Manager
- Unmount an EFI partition

It can currently perform some very basic actions, but it will get more and more advanced later in time.

### Used tools

To get its job done, LinuxEFIMounter utilizes a bunch of GNU/Linux's **preinstalled tools**, such as:

- fdisk
  
  > It is used to get the list of disks and partition on your PC.

- git
  
  > Utilized to check and install new updates.

- xdg-open
  
  > Basic command to open your default file manager in a specific directory.

### Use cases

LinuxEFIMounter is the perfect solution for a variety of problems.
You can use it to:

- Fix your Hackintosh if it's not booting and you have no idea how to access the EFI folder
  
  > If you fuck up with your kexts, SSDTs or drivers (like I did) you will likely need a quick way to fix them to make your Hackintosh ready again.

- Clean up your EFI
  
  > If you've ever done Hackintoshing before, you'll be familiar with those annoying logs left by OpenCore every time you boot your Hackintosh. With LinuxEFIMounter you can get rid of them in under than 1 minute!

- Add files to your EFI
  
  > It's pretty similar to Point 1, both points focus on the ease of access to your EFI folder while on a Linux environment.

- Manage your Windows or Linux EFI folder
  
  > That's right, LinuxEFIMounter can mount all kinds of EFI partitions you can think of!
  > The program might often refer to the EFI partition as *"the Hackintosh EFI partition"* or to the drive as *"your Hackintosh disk"*, but you can use it for   non-Hackintosh systems too.
