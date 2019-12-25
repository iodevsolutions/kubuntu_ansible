## Add Ansible repository (ie. Ubuntu/Debian)
```Shell
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
```

## Install Ansible package
```Shell
sudo apt-get install ansible
```

## Apply Ansible playbook
```Shell
sudo ansible-pull -U https://github.com/iodevsolutions/kubuntu_ansible.git
```
