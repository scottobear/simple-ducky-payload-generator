# Accessing and maintaining the Pure-FTPD Server #

The Pure-FTPD server is designed for the credential stealing payloads. When setting up your ftp server think about where your credentials are going to be input... That's right you guest it, the VICTIM's machine. With that said don't use; your everyday user account, your real name, real passwords or other identifying information. It is possible for these credentials to come back and haunt you as they will be sent unencrypted over the network. Note: Pure-FTPD is not installed in Kali by default, to install  **apt-get install pure-ftpd**

When in doubt use the credentials of;

  * username: hacker
  * password: hacker


## I messed up my FTP Server! What do I do?!?! ##

So you messed up your server, huh? This fix is simple run the following in your terminal:

  * root@kali:~# pure-pw userdel usernameofyourftpaccount
  * root@kali:~# userdel ftpuser
  * root@kali:~# groupdel ftpgroup
  * root@kali:~# rm /etc/pure-ftpd/auth/60pdb
  * root@kali:~# rmdir /ftphome/

Once you are done go back through the FTP Server Setup process.