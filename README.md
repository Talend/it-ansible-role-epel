Ansible Role EPEL
=========

[![Build Status](https://travis-ci.org/mmahfoudi/ansible-role-epel.svg?branch=master)](https://travis-ci.org/mmahfoudi/ansible-role-epel)

Installs the EPEL repository for RHEL systems.

Requirements
------------

The operating system must be any Linux distribution that are based on the source code of RHEL.  

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible-role-epel }

License
-------

MIT

Author Information
------------------

Mehdi MAHFOUDI (mmahfoudi@talend.com)
