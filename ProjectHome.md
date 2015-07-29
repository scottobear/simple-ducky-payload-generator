# Simple-Ducky Payload Generator #

The simple-ducky is the ultimate companion for the USB Rubber Ducky. It's an open source tool designed to help penetration testers when performing a physical access security audits. It allows them to quickly create reliable, customized payloads for just about any attack. The Simple-Ducky supports most Debian based Linux distro's.


### With the simple-ducky in a matter of seconds you can; ###

  * Create your evil executable (its automatically placed in your web directory)
  * Create your inject.bin
  * Launch a listener (meterpreter or netcat)
  * Generate custom password list's
  * Crack extracted passwords
  * And so much more...


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




## Videos ##

I will post more videos as time goes on...

### Simple-Ducky v1.1.1 Showcase Video ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=ch60ar30BPY' target='_blank'><img src='http://img.youtube.com/vi/ch60ar30BPY/0.jpg' width='425' height=344 /></a>

### Kali-Linux Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=KBwdkYAn9QY' target='_blank'><img src='http://img.youtube.com/vi/KBwdkYAn9QY/0.jpg' width='425' height=344 /></a>

### Linux Mint Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=TPpe0fHN8iY' target='_blank'><img src='http://img.youtube.com/vi/TPpe0fHN8iY/0.jpg' width='425' height=344 /></a>

### Ubuntu Install ###

<a href='http://www.youtube.com/watch?feature=player_embedded&v=RGmAkIltYRs' target='_blank'><img src='http://img.youtube.com/vi/RGmAkIltYRs/0.jpg' width='425' height=344 /></a>


If you would like to contribute your payload to the Simple-Ducky please contact me - skysploit@gmail.com