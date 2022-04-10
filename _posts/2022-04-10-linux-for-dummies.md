## What is Linux?

Linux is an open-sourced OS, written 98% of the code in `C Programming Language` invented by **Linus Torvalds**.
Linux source code is available [here](https://github.com/torvalds/linux)

The structure of the linux code
![Linux][logo]

[logo]: /img/linux/linux_filestrucure.png "Linux File Hierarchy"

Will discuss about key things in Linux from the above image further in our discussion. 

### Why Linux?
There are many reasons for Linux to be extremely popular, will try to list key factors here:
1. Linux has less security flaws
   * As Linux is Open-Source code, huge number of developers will review the code constantly
   * Linux has password authentication, file system discretionary access control, and security auditing, these 3 fundamental security features are essential

2. Linux is Free OS
   * Linux has no license cost to use it unlike other OS like Windows it is free

3. Performance
   * Linux doesn't have bloat UI features which makes it light weightLinux can run on almost any architecture (`x86`, `ARM`, `RISC-V` .. etc)
   * Linux has organized file system hence it is easy to perform file operations quickly  

4. Task Automation
   * Because of default shell (`bash`, `zsh`, `sh` .. etc) support in Linux, users can automate most of the regular stuff efficiently on Linux

### How to Install Linux
There are many varients of Linux is available for public. why?
   * Why there are so many cars? Because there are several vehicle manufacturers using the `Linux engine` and each of them has different types and for different purposes. Since the `Linux engine` is free to use and modify, anyone can use it to build a vehicle on top of it.

For Servers: CentOS 8 (RHEL without License) is most widely used across data centers.

   * To Install it on Server: [Guide](https://linuxhint.com/install_centos_8_server/)
   * To Install it on Laptop/Desktop: [Guide](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview) 

### Basic commands 
#### Create New User
Note: To create new user, we need to have sudo permissions on the machine
``` Shell Commands
useradd mohan          # Creates username
groupmod  mohan        # Creates Group name
passwd mohan           # Asks for user input to set password
mkdir /home/mohan  -p  # Creates user space under home
chown -R mohan:mohan /home/mohan  # Setup group policies 
usermod -d /home/mohan -m mohan   # Modifies user login
sudo chsh -s /bin/bash mohan      # Change default shell to bin/bash  
```
