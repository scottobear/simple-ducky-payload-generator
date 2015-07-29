# ~Persistence~ #

The simple-ducky's flagship payload is called ~Persistence~. Persistence, is a great payload that gives you a reverse shell every time a user logs into the victim machine. Since persistence creates an admin account no matter what the users privs are you can always do a runas to escalate privileges. What about anti-virus?? Well, persistence uses a legit windows binary called Netcat most (if not all) anti-virus software see it as harmless and lets it right on through. What else does Persistence do? Well this is exactly what persistence does from start to finish;

  1. Opens an admin command prompt
  1. Creates an admin user (It is even designed to take long 15+ character           passwords, incase the network being tested has a complex password policy)
  1. Disables the Windows firewall
  1. Enables Remote Desktop
  1. Enables Remote Assistance
  1. Hides the newly created admin account from the Windows Welcome Screen
  1. Creates a VBScript to run a hidden instance of Netcat
  1. Creates a batch file to launch Netcat (this is needed to mask an open   Netcat session from the desktop)
  1. Downloads Netcat from the attackers web server
  1. Calls the VBScript to launch the hidden netcat shell (you can send   the shell to an IP address or a domain address i.e. my.no-ip.org)
  1. Creates a batch file in the startup directory that will launch the VBScript every time a user logs in (the batch file is hidden/transparent   to the user while it runs)

## What files do remove after I am done with the victim machine? ##

Persistence leaves behind four files. Here are the names and locations of the files;

  * c:\Windows\System32\nc.vbs
  * c:\Windows\System32\nc.exe
  * c:\Windows\System32\nc.bat
  * c:\Documents And Settings\All Users\Start Menu\Programs\Startup\persistence.bat