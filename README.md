# WordPress Docker Ansible

## Prerequisites

1. Make sure vagrant is installed(not required if you want to use some other server).
2. Make sure Ansible is installed.

## Start virtual machine

```bash
vagrant up
```

## Running the Ansible Playbook

```bash
ansible-playbook server.yml -i inventory
```
