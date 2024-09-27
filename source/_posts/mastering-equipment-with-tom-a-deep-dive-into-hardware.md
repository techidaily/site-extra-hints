---
title: Mastering Equipment with Tom - A Deep Dive Into Hardware
date: 2024-09-03T08:20:08.253Z
updated: 2024-09-04T08:20:08.253Z
tags:
  - desktop
categories:
  - hardware
thumbnail: https://cdn.mos.cms.futurecdn.net/nbZh2NzQTFHsme5Q5oms2S-320-80.png
---

## Give New Life to Vintage Computers Using Damn Small Linux - Easy Setup Tips

Damn Small Linux is a lightweight Linux distro aimed at older and lower spec PCs just like the Asus Eee PC that we have from 2007\. The last release was way back in 2012, and since then the project has been on hiatus. Originally weighing in at 50MB back in 2012, Damn Small Linux 2024 Alpha release is a bulkier 700MB, and this hard limit means that it can be written to a blank CDR.

 Based on Debian and antiX,[Damn Small Linux 2024](https://www.damnsmalllinux.org/) uses Fluxbox and JWM window managers. These are lightweight alternatives to Gnome, KDE etc and are often used for distros targeting lower spec machines. There is a limited range of pre-installed software, covering web browsers, text editors, code editors, media playback and email. Because it is a Debian-based system, we can install applications using the apt package manager.

 The Asus Eee PC 4G was the first netbook from Asus and it contained an Intel Celeron 900 MHz CPU, but this was underclocked to 700 MHz to save power. Originally shipping with 512MB of RAM, our unit has been upgraded to 1GB. An internal 4GB eMMC is our only means of storage.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/JNKozDryqKdwftuyVWAqV5-320-80.png)

 (Image credit: Tom's Hardware)

 Damn Small Linux 2024 runs well on the venerable Asus Eee PC. Basic web browsing, text editing and general computing tasks are achievable. More advanced tasks, high definition video and image editing will depend on the age of your machine. On the Eee PC we found YouTube playback was not possible, because the CPU wasn’t strong enough to load all of the page elements. A newer machine is required for that. Something from the early 2010s, perhaps a Core2Duo or better and you have a workable spare machine.

 LATEST VIDEOS FROM tomshardware Tom's Hardware

## For this project you will need

* A USB stick (1GB or greater)
* An old PC with 4GB or greater HDD / SSD
* 1GB or more RAM
* Internet connection (Ethernet or Wi-Fi)

## Creating a Damn Small Linux 2024 boot USB

 The first step in the process is to create a bootable USB stick and for this we will need the Damn Small Linux 2024 ISO image and a copy of Rufus. Rufus will write the ISO image to the USB stick so that we can boot from it.

 1.**Download the latest ISO version of** [**Damn Small Linux 2024**](https://www.damnsmalllinux.org/2024-download.html) **to your computer.**

 2.**Download and install** [**Rufus.**](https://rufus.ie/en/)

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Stay On the Cutting Edge: Get the Tom's Hardware Newsletter

 Get Tom's Hardware's best news and in-depth reviews, straight to your inbox.

 Contact me with news and offers from other Future brands  Receive email from us on behalf of our trusted partners or sponsors

 By submitting your information you agree to the[Terms & Conditions](https://futureplc.com/terms-conditions/) and[Privacy Policy](https://futureplc.com/privacy-policy/) and are aged 16 or over.

 3.**Insert a USB stick (1GB or larger) and open Rufus.**

 4.**Select your USB stick as the Device** , then for Boot Selection**select Disk or ISO image and click SELECT.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/baQXPzYCDw9eq9wf9YrQXA-320-80.jpg)

 (Image credit: Tom's Hardware)

 5.**Select the Damn Small Linux 2024 ISO image and click Open.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/j3mBhzFS7tmDqEckBrWdQA-320-80.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 6.**Click START** to write the ISO to the USB stick. The ISO image is only 700MB and won’t take long to write to the USB stick. When done,**click CLOSE to exit Rufus.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/yu9EYu9BTTuGGjBtXNuEJA-320-80.jpg)

 (Image credit: Tom's Hardware)

 7. **Remove the USB stick from the computer and insert it into the recycled machine.**

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Installing Damn Small Linux 2024

 Now that we have a bootable USB stick, our focus moves to the old PC that we wish to reuse. We will first boot from the USB stick and ensure that it reaches the Damn Small Linux 2024 desktop.

 1\. With the USB stick inserted, **power up the computer and press the correct key to enter the boot selection.** The key can be ESC, F2, DEL or F12\.

 2.**Select Damn Small Linux 2024, hacked from antiX 23** and**press Enter.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/VX3He6Ti2rXuBRUXryans9-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Wait for Damn Small Linux to boot** and**click on the Installer icon** to start the installation process.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/8ruHFaJdsNupjFtvbQehm9-320-80.png)

 (Image credit: Tom's Hardware)

 4.**Wait for the installer to check your installation media** (the USB) for errors.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/PvyNXHHvZqzg9U2xzwU9CA-320-80.png)

 (Image credit: Tom's Hardware)

 5.**Set your keyboard layout and click Next when ready.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/pyrBdYG3Uqu4UxbURuo5U9-320-80.png)

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 6. **Install Damn Small Linux to use the entire hard drive and click Next to progress.** Advanced users may want to dual boot with another Linux distro or Windows, or to only use a partial amount of the drive. This is left as an exercise for advanced users.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/yqysCHTCs2mmqroE2YtZL9-320-80.png)

 (Image credit: Tom's Hardware)

 7.**Click OK to format the drive.** This will prepare the drive for the Damn Small Linux installation process.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/8HggdEvF2DKDFVbUVmCqB9-320-80.png)

 (Image credit: Tom's Hardware)

 8\. While the installer copies the files,**setup your locale and timezone then click Next.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/2zBeZ2Ezr6diBMHTuYQZ39-320-80.png)

 (Image credit: Tom's Hardware)

 9. **Next setup your unprivileged user, and optionally a root user account. Click Next to move on.** Your unprivileged user is automatically added to the sudo group and so can temporarily elevate their privileges. But often, having a root admin user is an extra level of[security](https://www.tomshardware.com/tag/security) should you accidentally break the main user account.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/bwm3cbDBvEeMPW7bFSGe3A-320-80.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918666/19272" target="_top" id="1918666">
  <img src="//a.impactradius-go.com/display-ad/19272-1918666" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918666/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 10. **Ensure that automatically reboot checkbox is checked, and click Finish to reboot.**

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/vVszmiobWW4GyN9D2xCLu8-320-80.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

<!-- affiliate ads begin -->
<iframe id="iframe_1834906" src="//a.impactradius-go.com/gen-ad-code/5597632/1834906/16836" width="728" height="90" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
## Using Damn Small Linux 2024 for the first time

 Damn Small Linux 2024 doesn’t feel too different from more mainstream Linux distros. It may look different when compared to the “high gloss” distros for more modern machines, but under the hood is Debian, and this makes us feel right at home.

 1. **If prompted on boot, select the Damn Small Linux 2024 option from GRUB.** GRUB is a boot menu where we can choose which operating system to boot from.

 2. **At the login prompt, enter your username and press Enter to move to the password box. Enter the password and press Enter to login.** Typically we would use TAB to navigate between the lines, but this did not work with Damn Small Linux.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/ZFdWZ4QpfABaJ9bbULSrk8-320-80.png)

 (Image credit: Tom's Hardware)

 3.**Left click on Menu to open the main menu.** You can also right click to bring up the menu at your current mouse position.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/G8vXVZ6gyiBBpriaEhooY8-320-80.gif)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

Quick links to apps are found at the top of the list.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/HqrNrNtz2VMYg9qbGtx8A8-320-80.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657400/16446" target="_top" id="1657400">
  <img src="//a.impactradius-go.com/display-ad/16446-1657400" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657400/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 The Applications menu contains all of the applications that come pre-installed. We can add more apps via the terminal. Underneath the desktop is a Debian install which we can update using the apt package manager. You will need an Internet connection before attempting to do this.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/PceAwi5SHK8ZN4cZQRRVS7-320-80.png)

 (Image credit: Tom's Hardware)

 1.**Right click and select Terminal from the menu.**

 2.**Update the repositories.** This checks our list of installable software against a list on a remote server.

```
sudo apt update
```

 3.**Search for an application.** We wanted to install the Geany text editor, so we searched the repositories for geany. **Scroll through the returned information to discover the application.**

```
sudo apt search geany
```

 4. **Install the app using apt. Press Enter to run the command, and wait for the installation to complete.**

```
sudo apt install geany
```

 5.**Run the app from the terminal using its name and press Enter.**

```
geany
```

 The alternative to the terminal is the Manage Packages application, found in the Control Center >> Software. This is a simpler, guided means to keep your system up to date.

 The Control Center is where we can make changes to the system. For example we can make Wi-Fi and Network connections, update system time and manage packages.

![Damn Small Linux](https://cdn.mos.cms.futurecdn.net/fpp3uEkLvKHzjMDdGUpkr7-320-80.gif)

<!-- affiliate ads begin -->
<iframe id="iframe_1743243" src="//a.impactradius-go.com/gen-ad-code/5597632/1743243/19272" width="250" height="90" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
 (Image credit: Tom's Hardware)

 Damn Small Linux 2024 is a fun way to resurrect an older machine. We wouldn’t spend our entire work day using such an old machine, but it can be useful to have a spare machine for the kids to hack on. It can also be useful when we need focus, a low-spec machine will struggle to run multiple applications, forcing us to complete a task.


<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>


