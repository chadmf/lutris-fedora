Role Name
=========

Fedora installer for Lutris for gaming

Requirements
------------

ansible >= 2.7

Role Variables
--------------

If fedora version != 33 fedora_version=<version#>

Dependencies
------------

NA

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
---
- name: Configure Lutris on Fedora
  hosts: localhost
  gather_facts: False
  become: yes
  roles:
    - lutris
```

License
-------

MIT

Author Information
------------------

https://github.com/chadhellyea/lutris-fedora/
