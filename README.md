# Ansible Network Configuration (IAC approach)
Using an Infrastructure as Code apporach to create a network on GNS3.

This will be to configure 3 Nexus 9ks as the core/distrbution switches and 1 Access layer ios switch, that will give connectivity to two virtual pc's. 

The confusing part of the topolgy will be the switch connected to everything, as this is providing a bridged connection to my private network, this enables me to use my MacBook for development and my home PC that has a lot of RAM to power the "lab". 

![Alt text](https://github.com/alexb2746/Ansible_Network_Configuration/blob/master/gns3_topology2.jpg)
