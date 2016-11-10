Ansible play book for controlling development, staging, and production environment automatically. Development environment is virtual machine on localhost and ip address setted to 10.0.0.13.
For now, it is able to control only development
and staging environment. This server is for MEAN server. So, it installs nodejs and mongodb on the servers.
Usages:
Setup development environment
- ansible-playbook -i inventories/development server.yml
Setup staging environment
- ansible-playbook -i inventories/staging server.yml
