---
title: 'How to run LinuxEFIMounter'
date: 2019-02-11T19:27:37+10:00
weight: 2
---

Before you run LinuxEFIMounter, you have to make sure it has the rights needed to be executed:

```bash
sudo chmod a+x LinuxEFIMounter.sh
```

It must be run as root. Run it with `sudo`:

```bash
sudo LinuxEFIMounter.sh
```

However, the script needs the **git** package to be installed. The installation process of a package may vary, but the syntax is usually:

```bash
sudo packagemanagername -option=install git
```

Here you have a few examples:

```bash
# Arch Linux
sudo pacman -S git

# Ubuntu and -based
sudo apt install git
```
