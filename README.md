Ansible role: docker
=========

[![CI](https://github.com/lukaskaplan/ansible-role-docker/actions/workflows/ci.yml/badge.svg)](https://github.com/lukaskaplan/ansible-role-docker/actions/workflows/ci.yml)

Ansible role for setting up docker.

Requirements
------------

None

Role Variables
--------------

All config options are described in the `defaults/main.yml` file.

Dependencies
------------

None

Installation
------------

Edit **requirements.yml** file:

```yaml
roles:
  - name: docker
    src: https://github.com/lukaskaplan/ansible-role-docker.git
```

```bash
ansible-galaxy install -r requirements.yml
```

Example Playbook
----------------

File **playbook.yml**:

```yaml
- name: Example playbook
  hosts: servers

  tasks:
    - name: Role docker
      ansible.builtin.include_role:
        name: docker
      # vars:
```

How to run it:

```bash
ansible-playbook playbook.yml
```

License
-------

MIT

Author Information
------------------

This role was created by [Lukas Kaplan](https://lkaplan.cz).
