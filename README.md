# Ansible Role: docker
=========

A simple Ansible role for installing Docker for RHEL/CentOS 7 and Debian 10.

- Install the necessary packages;

Requirements 
------------

The SELinux and firewall settings are not considered to be a concern of this role.

Role Variables []
--------------

Dependencies
------------

You need to install python-apt package on debian 10 


Example Playbook
----------------

---
- hosts: redhat,debian

  become: yes

  roles:

    - /path/docker

...

Example inventory
-----------------
[redhat]

node_redhat

[debian]

node_debian

## Contributing

Issues, feature requests, ideas are appreciated and can be posted in the Issues section.


Author Information
------------------
LinkedIn: https://br.linkedin.com/in/almircandido

