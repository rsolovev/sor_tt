# Soramitsu test task

Ansible playbook with 2 roles:
1. Install and configure docker (latest stable)
2. Clone, build and run containerized python app 

playbook is considered to run locally (for simplicity - hosts: 127.0.0.1)

to run playbook on server:

```shell
ansible-playbook playbook.yml -f 10
```
