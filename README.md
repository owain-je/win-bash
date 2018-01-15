# win-bash
## Local development
-----------------

- Virtual box  / vagrant images often expired  
- Vagrant - very few hyperv images (build your own) 
- Disk space consumption 30G absolute Minimum vs <8 for linux 
- Powershell vs other - having to support and learn multiple scripting languages  
- Docker locally needs to have hyperv - loss of virtual box 
- Hyper v not feature compatible with virtualbox 


## Operations
----------

- Time to install windows updates - many many minutes 30 to 2hrs or more depending 
- Hard to determin when windows updates are complete , difficult to script. 
- Boot up times - be default 7+ minutes 
- lack of control (reboot vs shutdown) 
- 64Bit hack of registry confusion easy to read or write to 32 bit registry when it needs to be 64bit (time wasted)  
- starting applications over winrm as 32 bit cannot launch 64bit application 
- Inability to install some applications via winrm (due to security updates policy over winrm) 
- Confusion - how do I configure somthing (registery, file, group policy) 
- Package management - chocolatey relies on downloading files from random websites 
- Many tools are charged for in windows. 
- AD only inbuilt LDAP authentication mechanisum , requires extra reboot +1m on boot up time 
- LDAP using pgina - hard to configure granular access in a simple way 
- Have to sys prep images - extra time on building images and amis 
- WINRM hard to use for non AD integrated machines vs ssh 
- RDP proxy - a paid for capability if you want jump boxes 
- Cannot install windows updates via winrm unless done async 

## AWS
--- 
- No Per second billing 
- No Instance class RI's buy machine type. 
- license fee cost built into run time cost 
- Disk usage costs of EBS 3 time more expensive than linux (10GB vs 30) 
