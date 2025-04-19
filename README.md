docker
=========

This role installs [Docker](https://www.docker.com) on Linux.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```yaml
---
- name: Install docker
  hosts: <host_or_group>

  tasks:
    - name: Install docker
      include_role:
        name: docker
...
```

License
-------

MIT

Author Information
------------------

This role was created by [Lukas Kaplan](https://lkaplan.cz/)