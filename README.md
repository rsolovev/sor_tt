# Soramitsu test task

Ansible playbook with 2 roles:
1. Install and configure docker (latest stable)
2. Clone, build and run containerized python app 


to run playbook on server:

```shell
ansible-playbook playbook.yml -f 10
```

playbook is considered to run on host machine with editted ```/etc/ansible/hosts``` file (server added there) 
(but for simplicity we can specify 
```yml
- hosts: 127.0.0.1
  connection: local
```
to make it local)
