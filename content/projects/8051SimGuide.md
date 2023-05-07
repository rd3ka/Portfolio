---
title: 8051SimGuide
description: Automation script for the use of edsim8051
dateString: April, 2020
tags: ["automation","mpmc", "python", "bash", "powershell"]
weight: 2
---

This project, rather this script, started off as a form of
help that I wanted to offer to my fellow University mates back during Engineering School.
We had a subject called Microcontrollers and Microprocessor (ECC403) in our curriculum. We had to deal with a
simulator which would simulate the working of 8051 Microcontroller. This simulator edsim51di was written in java.

And most of my peers found it difficult to run this piece of software as it was packaged as a jar file and required some command line tinkering. As most programmers who are starting out, they were petrified from the command line. They found it difficult to run this simulator. This is when, using the power of automation and my little knowledge of Operating System, I made the 8051SimGuide Script


# 🔗 [Main Branch](https://github.com/rd3ka/8051SimGuide/tree/master) :

## Dependencies

This python script is 95% pure i.e does not use any external 
libraries expect for one, ['ProgressBar'](https://pypi.org/project/progressbar2/)


To run the unpackaged script, install the below dependencies via pip/easy
```bash
pip install progressbar2
```
If pip is not available, use easy
```bash
easy_install progressbar2
```
Note: Setting up a `venv`
i.e virtual environtment is recommended

## Screenshots
 🔗 [8051SimGuide.py](https://github.com/rd3ka/8051SimGuide/blob/master/8051SimGuide.py)

![screenshot_01](https://user-images.githubusercontent.com/44165144/201349573-15e1c031-5dfc-4128-8658-e59ed6d6fce6.png)

# 🔗 [v2 Branch](https://github.com/rd3ka/8051SimGuide/tree/v2) :

At the time of writing the script, I was still a student and was trying out different things to work on, so that I could improve on my programming skills. Hence, after 2 years of the original script. I've learnt a lot and gathered a lot programming experience, as when compared to the time of writting this script. This has led me to use shell scripting using bash shell to redo my original script which in turn optimizes the code count and also the performance without any overhead dependencies.

## Installation & Dependencies

**Linux** : The script was made to run in bash shell which is the default shell is most modern distributions.
 ```curl``` , ```tee```, ```ping```, ```zip``` and ```tar```
command line programms are used. These command line programs come preinstalled and are essential part of the kernel in most 
distributions.

In case, the script errors out, please installed them manually in accordance to your distro:

```
Debain/Ubuntu : sudo apt-get install curl, tee, ping, tar
Arch          : sudo pacman -S curl, tee, ping, tar
Fedora/RedHat : sudo dnf install curl, tee, ping, tar
```
Before running the script don't forget to change the execution group/policy
```
chmod +x 8051SimGuide.sh
```

**Windows** : The script was made using ```powershell```, so 
no additional dependencies are required to be met.

## Screenshots
🔗 [8051SimGuide.sh](https://github.com/rd3ka/8051SimGuide/blob/v2/8051SimGuide.sh)

![screenshot_02](https://user-images.githubusercontent.com/44165144/201364637-f5a0e490-366d-471d-92b1-2779d96aad4f.png)

NOTE: 🔗 [8051SimGuide.ps1](https://github.com/rd3ka/8051SimGuide/blob/v2/8051SimGuide.ps1) does not have any Command Line Interface or GUIs