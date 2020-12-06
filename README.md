# Soramitsu test task

Ansible playbook with 2 roles:
1. Install and configure docker (latest stable) and docker-compose (for nginx + app)
2. Clone, build and run containerized python app (with nginx as proxy)


to run playbook:

```shell
ansible-playbook playbook.yml -f 10
```

NOTE: playbook is considered to run on host machine with editted ```/etc/ansible/hosts``` file (server added there) 
(but for simplicity we can specify 
```yml
- hosts: 127.0.0.1
  connection: local
```
to make it local)
