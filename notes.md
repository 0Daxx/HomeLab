
### Current system info   as of Nov 2 , 26 
- fedora 42 
- 




## 2026-11-02 22:47
- installed a virtual 

### Linux 
- update debian based 
`sudo apt-get update && sudo apt-get upgrade -y `  
- command to check the ip address of current system 

- find ip of virtual machine 
https://www.geeksforgeeks.org/linux-unix/command-to-check-ip-address-in-linux/
` hostname -i  `


- Ip address : 192.168.122.203 


## TASK 2 : Copy ip address from virtual machine to here 

## TASK 3 Increase font of virtual  machine server 

- https://askubuntu.com/questions/1402246/how-change-the-font-size-in-ubuntu-server-20-04-lts

` sudo vi /etc/default/console-setup FONTFACE="Terminus" FONTSIZE="16x32" sudo update-initramfs -u sudo reboot `

## TASK 4 :  Check disk usage 

- `df -H `
![task4](task4.png)

- https://opensource.com/article/18/7/how-check-free-disk-space-linux

## ssh into the homelab 
- Public ip of  current system and home lab 
  - -   `curl ifconfig.me `  
    Why not `hostname -i ` 
    - - 
- command of ssh to connect 
  - ssh <user>@ip_address 

- 







