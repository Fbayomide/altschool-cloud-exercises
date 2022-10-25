## [Exercise]() 1
### Task: 
* Setup Ubuntu 20.04 LTS on your local machine using Vagrant
### Instruction: 
- [ ] Customize your Vagrant file as necessary with private_network set to DHCP.
- [ ] Once the machine is up, run ifconfig and share the output in your submission along with your Vagrant file in a folder for this exercise.  

## Solution  


I configured the **"private_network"** to **"dhcp"** by editing the **vagrantfile** manually. Below is the outcome.    

 ![Vagrantfile - Notepad 8_23_2022 4_23_29 AM](https://user-images.githubusercontent.com/67663655/186158896-991553c3-9180-4470-802d-17b273d34104.png)


I had to install **net-tools** before running the **$ ifconfig** command. So i installed **net-tools** by doing **sudo apt install net-tools**. After that, i ran the **$ ifconfig** command and below is the outcome.  

![ifconfig command](https://user-images.githubusercontent.com/67663655/186159000-bf84aaa8-5099-418c-a75f-9c14a20ef1dd.png)
