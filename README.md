Role Name
=========

This role will install mysql for wordpress deployment

Requirements
------------

Python> 2.7
Ansible version >= 2.10

Role Variables
--------------

Variables are defined in the vars/main.yml directory for DB creation and user creation

Dependencies
------------

No pre-req dependency required

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: all
  become: true
  roles:
   - mysql


License
-------

BSD

Author Information
------------------

Created by DevOps Trainer- Sonal mittal
