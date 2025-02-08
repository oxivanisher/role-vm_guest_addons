vm_guest_addons
===============
[![Ansible Lint](https://github.com/oxivanisher/role-vm_guest_addons/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-vm_guest_addons/actions/workflows/ansible-lint.yml)

Install virtualization guest addons based on `ansible_virtualization_type`. This is meant to be extended when the need arises. Currently it supports the following virtualization environments:
* kvm

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------
```yaml
- name: Install virtualization extensions
  hosts: vms
  roles:
    - role: oxivanisher.linux_base.vm_guest_addons
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
