# How to change hostname in Linux

### Change hostname manually:
     vi /etc/hosts 127.0.1.1 <your-old-hostname> replace it youe <new hostname>
     vi /etc/hostname
     sudo reboot
     
### Change hostname via command line:
Step_1: Check the current hostname:

    hostnamectl
Step_2: Change the hostname Replace new-hostname with your desired hostname:
    
    sudo hostnamectl set-hostname rafsan
Step_3: Verify the changes, You can check if the hostname has been updated by using hostnamectl again:

    hostnamectl    
Step_4: Reboot your system

    sudo reboot
