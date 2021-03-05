# remove-fw-licenses-cert
Ansible script to run a few commands needed to connect delete and re-fetch firewall license keys and delete logging-service certificate.
### REQUIRES
* ansible (v 2.9) (sudo apt-add-respository --yes ppa:ansible/ansible ; sudo apt update ; sudo apt install ansible)
* palo ansible role (sudo ansible-galaxy collection install paloaltonetworks.panos)
* python (tested with version 2.7.12)
* python pip (tested with version 8.1.1 for 2.7) 
* pandevice python package (sudo -H pip install pandevice)
* ansible (v 2.9) (`sudo apt-add-respository --yes ppa:ansible/ansible ; sudo apt update ; sudo apt install ansible`)
* palo ansible role (`sudo ansible-galaxy collection install paloaltonetworks.panos`)
* python (tested with version 2.7.12) (`sudo apt install python`)
* python pip (tested with version 8.1.1 for 2.7) (`sudo apt install python-pip`)
* pandevice python package (`sudo -H pip install pandevice`)


### STEPS
