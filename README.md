# remove-fw-licenses-cert
Ansible script to run a few commands needed to connect delete and re-fetch firewall license keys and delete logging-service certificate.

### REQUIRES
* ansible (v 2.9.18) (sudo apt-add-respository --yes ppa:ansible/ansible ; sudo apt update ; sudo apt install ansible)
* palo ansible role (sudo ansible-galaxy collection install paloaltonetworks.panos)
* sudo ansible-galaxy install PaloAltoNetworks.paloaltonetworks
* python (tested with version 2.7.17)
* python pip (tested with version 9.0.1-2.3) 
* pandevice python package (sudo -H pip install pandevice)

### STEPS
* update `vars.yml` with valid user/password
* update `hosts` with list of firewall ip addresses
* update *ansible_python_interpreter* in the playbook with correct location of python (default locationis /usr/bin/python)

### EXECUTE
```
ansible-playbook -i hosts connect-fw-to-cdl.yml 
```
_This code is my own. Provided without warranty or affilitation with Palo Alto Networks._
