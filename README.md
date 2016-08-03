ansible-role-zabbixAgent
=========
[![Ansible Role](https://img.shields.io/badge/role-louwandre90.zabbixAgent-blue.svg?style=flat-square)](https://galaxy.ansible.com/louwandre90/zabbixAgent/)

This role installs Zabbix Agent on Debian:

Installation is done via apt and some configuration is done after installation. 

Requirements
------------

None

Role Variables
--------------

The following defaults are set:

    username: jarvis

To pass different variables:

    ansible-playbook playbook.yml -e 'username=myuser'
    
Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: louwandre90.zabbixAgent }

License
-------

BSD

Author Information
------------------

This role was created in 2016 by Andre Louw.
