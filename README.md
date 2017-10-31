# devops-test-task #

This is testing playbook for deploying django sample app: https://github.com/geri4/django-sample-app 

## Pre requirments ##
Client:
- Ansible 2.4

Server:
- Ubuntu 16.04
- Python 2
- sudo

## Deploy ##
1. Add server to hosts file inside django group. For example:
```
ubuntu ansible_ssh_host=1.2.3.4 ansible_ssh_port=22
```

2. Run deploy:
```
ansible-playbook main.yml
```

3. Enter user password, sudo password and vault password.
