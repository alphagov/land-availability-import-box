# land-availability-import-box
Land Availability Import Box - Ansible scripts to setup a box to import data

# Requirements

## Developer Machine
This script needs Ansible installed. The advice is to create a virtualenv and
install it from pip:

```
pip install ansible
```

## Remote Machine
On the remote machine, Python 2.7 is required to make Ansible work

```
sudo apt-get update
sudo apt-get install python-minimal
```

# Usage

```
ansible-playbook -i '54.210.234.125,' -u ubuntu playbooks/lat-client.yml
```
