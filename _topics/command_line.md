---
topic: "Command Line"
desc: "We do lots of stuff 'at the command line' in CS courses at UCSB... "
---

# How to code through the command line for Mac

For Mac users, you can easily pull up the command terminal and simply start typing linux commands.

# How to code through the command line for Windows

Unfortunately for Windows users, you have to jump through a couple more hoops to successfully code through the command line.
*If you opened the command terminal on a Windows computer, the terminal would not recignize any of the commands you use*

Thankfully, there are a TON of different options for how you can go about this:


* [MobaXTerm](https://mobaxterm.mobatek.net/) is a software that combines both ssh and X11. See below for tutorial to set it up
* Putty with XMing is also software you can download. See [link](https://foo.cs.ucsb.edu/56wiki/index.php/CSIL_Access:Windows) for tutorial 
* [Git for Windows](https://git-scm.com/) gives you a bash shell with a bunch of the normal Unix commands
* Ubuntu Windows Subsystem may be a thing on your system
* Cygwin is an option
* You could run Linux in a virtual machine on your computer

# How to download MobaXTerm and connect to CSIL

Click this [link](https://mobaxterm.mobatek.net/download-home-edition.html) and download MobaXTerm on your computer.
Once downloaded and installed, open up the software.

To start using CSIL, you must ssh into your account. There are two ways to do this with Mobax:


1. Click on "Session" on the top lefthand corner, then "SSh" in the top left-hand corner of the window that pops up. Under "Remote Host" put your csil account WITHOUT your username (something like csil-01.cs.ucsb.edu) then press ok. A command line will pop up asking your your CSIL username and password.

OR

2. Simply click "Start Local Terminal" from the home page. Type in the command `ssh username@csil-01.cs.ucsb.edu` It will ask for your password.



