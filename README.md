open_vm_tools
=============

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
