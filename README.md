# How to change hostname via command line in Linux:

Step_1: Check the current hostname:

    hostnamectl
Step_2: Change the hostname Replace new-hostname with your desired hostname:
    
    sudo hostnamectl set-hostname rafsan
Step_3: Verify the changes, You can check if the hostname has been updated by using hostnamectl again:

    hostnamectl    
Step_4: Reboot your system

    sudo reboot
