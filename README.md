# switch-net
### Author:	@R3MRUM
### Decription:
This is a little script that I wrote which enabled me to quickly switch between a static IP and a dynamic IP. I would switch to DHCP when I needed to connect to the internet in order to update my analysis tools on my linux VM and then switch back to a static ip to move the VM back into Host-Only isolation. The primary benefit to this script versus doing it manually is the use of a config file to store static IP properties.

The static IP properties you define are saved within "~/.switch-netrc". Below are the default properties should you not supply any:
  
  * interface:	eth0
  * ip: 		172.16.0.131
  * subnet:		255.255.255.0
