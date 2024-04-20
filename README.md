# Environment setup script

Ansible script to setup my environment in Kubuntu

## Requirements

### Install Ansible

`sudo apt install ansible`

### Set username

Inside `./var/main.yml` set `default_user` to your username

## Run all roles

`ansible-playbook setup.yml`

### Run a tagged role

`ansible-playbook setup.yml --tags <tag-name>`

### Create new role

`ansible-galaxy init <role-name>`
