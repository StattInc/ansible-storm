# ansible-storm
Configuration for deploying a Storm cluster with Ansible

ansible-playbook -i hosts storm-playbook.yml

Clone https://github.com/elastic/ansible-elasticsearch
and create link to /roles

ansible-playbook -i hosts es-playbook.yml

```
[storm-master]
xxx.xxx.xxx.xxx ansible_become=true ansible_user=julien

[storm-slave]
xxx.xxx.xxx.xxx ansible_become=true ansible_user=julien
```
