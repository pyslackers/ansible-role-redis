pyslackers.redis
=========

Role to install and configure redis on a local machine (this does not currently support clustering).

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

* [`pyslackers.common`](https://github.com/pyslackers/ansible-role-common)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - role: pyslackers.redis
```

License
-------

MIT

Author Information
------------------

https://pyslackers.com
