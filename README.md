# linux_faq
I have recently installed Ubuntu and am sharing my Linux related answers here

---

sudo apt-get install vlc'
or sudo apt update 
[sudo] password for username:
E: Could not get lock /var/lib/apt/lists/lock - open (11: Resource temporarily unavailable)
E: Unable to lock directory /var/lib/apt/lists/

just write this:
sudo fuser -vki /var/lib/apt/lists/lock
