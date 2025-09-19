# Cybernet Virtual Lab Project

This project was personally constructed through various resources I found going through and learning about different concepts on how to make my own virtual labratory of VMs. I used VirtualBox along with two different kali machines in order to set the foundation for what this network will become.

The internal network was set for these machines in order to isolate them from the internet constituting a controlled environment to experiment and test commands in.

I utilized the virtual box command line tool to set up a DHCP server in order to assign IP/4 addresses to the VMs.

Once both boxes had been configured, I tested through connection with the `ping` command as well as `nmap`, started a python http server one and scanning for that open port from the other.
