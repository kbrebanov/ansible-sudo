sudo
====

[![Build Status](https://travis-ci.org/kbrebanov/ansible-sudo.svg?branch=master)](https://travis-ci.org/kbrebanov/ansible-sudo)

Installs and configures sudo.

Requirements
------------

This role requires Ansible 1.9 or higher.

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Install sudo
```yaml
- hosts: all
  roles:
    - kbrebanov.sudo
```

License
-------

BSD

Author Information
------------------

Kevin Brebanov
