Gartner Catalyst 2016
August 15-18
Docker Mobility Workshop
Anna Belak
Tony Iams

STEP 0:

You must have virtualization enabled in your BIOS for VirtualBox to work
correctly for this exercise. Docker requires a 64-bit OS. If you have
never run Docker in a VM on your computer before, you will need to reboot,
enter BIOS, and enable the appropriate features.

NOTE:

We will NOT be using Docker for Mac or Docker for Windows. If you already have
these set up on your system, you are welcome to try to follow along, but we
will  most likely be unable to help you resolve problems. What we will do is 
stand up a full VM using VirtualBox so that we have a nice and easy sandbox 
to play with.

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
$                                                                            $
$                       *~* MAC & WINDOWS USERS *~*                          $
$                                                                            $
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

You will need a Linux Virtual Machine and a terminal. We recommend that you
use VirtualBox and PuTTY. In theory, VMware Workstation should also work,
but we will not be able to troubleshoot it for you.

1) Install VirtualBox
2) Import the CentOS VM into VirtualBox and boot it
3) Configure the network under Settings to use the correct adapter
   "Cable connected" box should be checked under "Advanced"
4) Login using provided credentials
5) Type "ip addr" into the command line to find your IP
6) [WINDOWS USERS] Run PuTTY
7) SSH to this IP as root
8) You should be ready to roll  

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
$                                                                            $
$                           *~* LINUX USERS *~*                              $
$                                                                            $
$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

NOTE: If you are running a supported distribution of Linux, you can install 
Docker directly on your hardware. WE DO NOT RECOMMEND THIS for the purpose of 
this exercise. It will be much easier to work with a clean VM.

1) Go to https://www.virtualbox.org/wiki/Download_Old_Builds_5_0
2) Download and install VirtualBox 5.0.26 for your distro
3) Follow the same instructions above as Mac/Windows folks
