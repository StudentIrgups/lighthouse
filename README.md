Role Name
=========

Role to deploy lighthouse on remote VM.

Requirements
------------

Ubuntu 2204.

Role Variables
--------------

defaults/main.yml 
  - repo_lighthouse - repo to get lighthouse
vars/main.yml
  - dest_lighthouse - path to keep config of lighthouse

Dependencies
------------

Nope

Example Playbook
----------------

```

- name: Install lighthouse
  hosts: lighthouse
  roles:
    - lighthouse
```

License
-------

MIT

Author Information
------------------

by Alex Beznosov for Netolgy
