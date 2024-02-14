# Description: This file contains the README for the project
This project is a small toy example for STIG compliance on a Ubuntu 20.04 lts system. This project uses ansible to configure the system to be compliant with the STIG standard. 
```


# Requirements
Ansible 2.9 or later
Vagrant 2.2.9 or later
Python 3.8 or later

# Quick Start

## Start Vagrant

```bash
vagrant up
``` 

Verify that the VM is running
```bash
vagrant ssh-config
``` 
## Ansible Inventory
```bash

``` 

Ping the VM
```bash
ansible -i hosts all -m ping
```  

run the playbook
```bash
ansible-playbook -i hosts stig.yml
```  
