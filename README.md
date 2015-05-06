open_vm_tools
=============

[![Ansible Galaxy](https://img.shields.io/badge/galaxy-kbrebanov.open_vm_tools-660198.svg)](https://galaxy.ansible.com/list#/roles/3477)

Installs open-vm-tools

Requirements
------------

This role requires Ansible 1.4 or higher.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Install open-vm-tools on VMware guest
```
- hosts: all
  roles:
    - { role: kbrebanov.open_vm_tools, when: "ansible_virtualization_type == 'VMware'" }
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
