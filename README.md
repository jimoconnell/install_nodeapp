# install_nodeapp
An ansible script to install a node app and run it using Ansible

# Hosts File
You will want to take file `hosts.example` and copy it to a file called `hosts`.  Edit that file to match your network.

#Running it all
To do the initial setup, run
```bash
ansible-playbook -i hosts playbook.yml
```


To start/restart the app servers (quicker) , run
```bash
ansible-playbook -i hosts startapps.yml
```
