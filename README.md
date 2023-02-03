Role Name
=========

Simple docker installation for a Raspberry Pi

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- name: Example Playbook
  hosts: somehosts
  become: true
  tasks:
    - include_role:
        name: roles/docker
```

License
-------

MIT

Author Information
------------------

Karsten A. M. Guenther (https://github.com/xxthunder)