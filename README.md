# How to change hostname in Linux

### Manual Process:
     vi /etc/hosts 127.0.1.1 <your-old-hostname> replace it youe <new hostname>
     vi /etc/hostname
     sudo reboot
     
### Command Line Process:
Step_1: Check the current hostname status:

    hostnamectl
Step_2: Change the hostname and Replace new-hostname with your desired name:
    
    sudo hostnamectl set-hostname rafsan
Step_3: Verify the changes, You can check if the hostname has been updated by using hostnamectl again:

    hostnamectl    
Step_4: Reboot your system

    sudo reboot
