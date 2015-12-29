# Piprobe management
#### Adapted from server_pi for use to manage the piprobe
####Ansible Playbook for management of a set of network probes based on raspian

First update the *hosts* file to use the IP's of your raspberry pi below the [pis] group,<br />
And edit the **/roles/piprobe/tasks/main.yml** file for your own users needs!

Once you've done that simply cd into the piprobe directory and run:
```bash
ansible-playbook piprobe.yml
```

Once it's complete, you should have a functional and up to date piprobe. You will need to expand your SD card as necessary to take advantage of a larger disk.

To complete the expanding of your SD card etc. Also make sure to change the password for the pi user! 

Verify it's me from my keybase.io page: https://keybase.io/buraglio<br />
Coffee always welcome or donate some bitcoin to the guy that I forked this from https://keybase.io/daniels 
