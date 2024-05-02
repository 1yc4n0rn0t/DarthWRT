# DarthWRT
## DarthWRT, an OpenWrt configuration for Raspberry Pi 4



One of the best ways to set up a home lab or to learn networking is by configuring everything yourself. A good friend of mine once opened my mind to the possibility of success through exceeding normal expectations. He did this by starting at the hardest level of something and then working his way down. Not everything will work out better this way, but when it comes to tackling big projects his philosophy fits. Networking is a tough skill to master. It can be a wonderful job or your worst nightmare. I started with a traditional router like most of you, but  I eventually made the switch to using open-sourced tools that helped me cover the knowledge gap. This file is a specially configured version of OpenWrt, built for a Raspberry Pi 4 motherboard. It ships with Luci and all the necessary components to get started. Just follow the instructions and you'll be on your way. 

```markdown

___  __ \_____ _________  /___  /_       __ |     / /________  /_
__  / / /  __ `/_  ___/  __/_  __ \________ | /| / /__  ___/  __/
_  /_/ // /_/ /_  /   / /_ _  / / //_____/_ |/ |/ / _  /   / /_  
/_____/ \__,_/ /_/    \__/ /_/ /_/       ____/|__/  /_/    \__/  

 |_  |    / /___\ \    |  _|
   | |_  / /|   |\ \  _| |  
   |  _|< < | | | > >|_  |  
  _| |   \ \|___|/ /   | |_ 
 |___|    \_\   /_/    |___|

       NO ONE IS SAFE  
-----------------------------------------------------
         %D %V, %C       
----------------------------------------------------- 



```    

        
Note* After you download the repoistory you will see that both files have been zipped. If you extract the vdi file it wont work for your virtualmachine, so just rename the file to .vdi and just discard the .gz 


### What you'll need



For this project to be effective, you will need the following items for the Raspberry Pi to be used as a networking device. 



1. A Raspberry Pi 4



![Image](https://github.com/justvincredible/DarthWRT/blob/main/DarthWrt/pi4.png)



2. DarthWrt File



```markdown

git clone https://github.com/Brilliance0nly/DarthWrt.git

```

3. Belena Etcher for flashing 



![Image](https://github.com/justvincredible/DarthWRT/blob/main/DarthWrt/etcher.png)



4. An SD card to install the system



5. A USB for expandiing storage and downloading packages 



6. An ethernet extender or portable switch







Install 



- Plug your Raspberry Pi into your router or modem then turn it on

- ssh into your device 



```markdown

opkg update

```



```markdown

opkg upgrade

```

- Reboot

- Find your IP address and type it into browser

- By default there is no password so you can just login , but the first administrator task is to set a root password

- Configure your settings
