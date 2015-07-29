This page will walk you through setting up and running the Simple-Ducky

# Introduction #

The simple-ducky is designed to quickly create reliable payloads and launch listener's.The Simple-Ducky currently uses version 2.6 of the duck encoder. The lastest version of the Simple-Ducky supports all Debian Linux distro's (i.e. Kali-Linux, Ubuntu, Linux Mint etc). The smart installer will take care of all the work for you.


## Dependencies ##

The following dependencies are automatically installed on version 1.1.0 and above;

  * Apache2
  * Pure-FTPD
  * Burp Suite
  * Social Engineering Tool Kit (SE-Toolkit)
  * Metasploit
  * p7zip-full
  * john
  * dfu-programmer
  * openjdk-7-jre-headless
  * samdump2
  * nmap
  * mingw32
  * bkhive

## To install the Simple-Ducky on any Debian Distro: ##

#### Install option 1 ####

  1. Download the install file: https://code.google.com/p/simple-ducky-payload-generator/downloads/detail?name=installer_v1.1.1_debian.sh&can=2&q=
  1. root@kali:~# chmod +x installer\_v1.1.1\_debian.sh
  1. root@kali:~# ./installer\_v1.1.1\_debian.sh
  1. root@kali:~# rm installer\_v1.1.1\_debian.sh
  1. To run the program; root@kali:~# simple-ducky

#### Install option 2 ####

  1. root@kali:~# git clone git://github.com/skysploit/simple-ducky.git /usr/share/simple-ducky
  1. root@kali:~# ln -sf /usr/share/simple-ducky/simple-ducky.sh /usr/bin/simple-ducky
  1. root@kali:~# Once installed run the simple-ducky by typing: simple-ducky

Note 1: Be sure to run option 9 "Dependency Checker" prior to running any other functions.

Note 2: If you have prior installs (v1.1.0 or prior) issue this command:
  1. root@kali:~# rm -rf /usr/share/ducky



### Kali-Linux Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=KBwdkYAn9QY' target='_blank'><img src='http://img.youtube.com/vi/KBwdkYAn9QY/0.jpg' width='425' height=344 /></a>

### Linux Mint Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=TPpe0fHN8iY' target='_blank'><img src='http://img.youtube.com/vi/TPpe0fHN8iY/0.jpg' width='425' height=344 /></a>

### Ubuntu Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=RGmAkIltYRs' target='_blank'><img src='http://img.youtube.com/vi/RGmAkIltYRs/0.jpg' width='425' height=344 /></a>