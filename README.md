# ansible-playbooks-ubuntu-cz

This repository contains Ansible playbooks to setup Ubuntu.cz servers.

## Requirements
- [Install `ansible`](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on your local machine.
- Have `ssh` and `sudo` access on the target servers.

## Run
```
$ ansible-playbook -i hosts.ini main.yml
```
