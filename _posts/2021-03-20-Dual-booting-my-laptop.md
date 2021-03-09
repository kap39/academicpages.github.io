---
title: 'Dual Booting my laptop'
date: 2021-03-20
permalink: /posts/2021/03/Dual-booting-my-laptop
  - How to Guide

---

Having used a linux machine exclusively for the past three years, I would be lying to say that I was thrilled about switching to Windows when I got my new laptop. As Windows 10 came pre-installed I decided to see how far I could get adjusting to using the 'user-friendly' OS.  There are certain aspects of using Windows that are definitely appealing, for instance Microsoft Teams now having more than 4 people on display, and how easy it is to install some software is absolutely delightful, and don't get me started on the Matlab GUI! However, I do miss the ability to customize the GUI within lubuntu, and using Git through terminal is just easier, though I do now understand the desktop app at least. 
I decided that three months was enough,though, and I'm now attempting to dual boot my machine. My previous installs of linux were relatively simplistic, since in my first machine I simply wiped the windows OS and replaced it with linux (it was a tiny hard drive and windows no longer fit: thus the switch), and then my last machine I managed to install a micro SSD allowing a dual hard drive run, so no partitioning was required. This time however, needs must I partition my SSD before dual booting, but I've already got windows installed. this post is to document my method should I need to replicate my movements. 

## Backing up windows
* Have an external hard drive ready with enough storage space on it (it doesn't wipe whats currently on there). 
* In settings, go to Update and Security. 
* In the sidebar, select Backup. 
* Click on 'Go to Backup and Restore (Windows 7)'. 
* Select 'Create a system image'. 
* Choose the external hard drive and click 'OK'. 

I don't know how to reinstall from this, but this should be a copy of the current files etc on windows.

## Creating a live USB
 * You need a USB that you can completely rewrite, with at least 4GB of storage (I went for an 8GB USB with an old boot I want to wipe on it).
 * First I installed [rufus](https://rufus.ie/), which is a software that allows you write bootable USBs. 
 * Download Ubuntu [here](https://releases.ubuntu.com/20.04/) by selecting the desktop image. Choose to save to downloads on your computer. DON'T SAVE TO THE USB. 
 * Open rufus and select the USB in 'Device'. 
 * Leave boot selection on 'Disk or ISO image (Please select)' and click the button SELECT next to it. 
 * Choose the iso Ubuntu file you downloaded in your Downloads folder. 
 * Hit the 'START' button at the bottom of the window.
 * Select 'Yes'
 * Click 'Ok' (should be on 'Write in ISO Image mode(Recommended)') - This will then wipe anything on the USB so move it before this point! 
 * It will take a while to copy all the files across so don't panic. Once the Status bar turns green, the USB is ready, so click 'Close' and remove the USB. 

 ## Dual Booting