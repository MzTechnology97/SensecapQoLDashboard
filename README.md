# Sensecap QoL Dashboard + Analysis log + Porting image Pisces on Sensecap #
E stato aggiunta l'analisi dei log di https://github.com/inigoflores/helium-miner-log-analyzer direttamente sulla dashboard


![image](https://user-images.githubusercontent.com/86824210/169501799-a2b12413-8a7d-4f4a-ba95-54b080c0fb2b.png)






## Installation Instructions ##

1. Find the internal IP address of your Pisces miner.
2. Use the following link, replacing __YOURIP__ with the IP address of your miner:
  - http://__YOURIP__/action.php?action=shell&cmd=wget https://raw.githubusercontent.com/MzTechnology97/SensecapQoLDashboard/main/install.sh -O - | sudo bash
3. Log in at https://__YOURIP__
  - Username: admin
  - Password: admin
4. Click "Tools"
5. Click "Reset Password"
6. Enter a secure password and click submit.
7. Enjoy!


## Updating ##

As of v0.1.1, the dashboard now has an updater.  If you are running version v0.1.0 then you will have to manually update this one.  Follow the instructions below:

1. Log in via SSH (either PuTTY or click start > type "cmd" and press enter, then type "ssh admin@your-miner-ip").
2. Run the following commands:
   - wget https://raw.githubusercontent.com/MzTechnology97/SensecapQoLDashboard/main/update.sh -O - | sudo bash

## Removal Instructions ##

1. Connect via SSH to your miner (either using PuTTY or open cmd and type:  ssh admin@YOURIP)
2. Enter the admin username and the password you set.
3. Type the following command:  sudo bash /var/dashboard/uninstall.sh
