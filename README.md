[![](https://github.com/ansible-roles-matsumura/vim/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Abuild)

Role Description
=========

Installs vim for CentOS7/CentOS8.

Requirements
------------

None

Role Variables
--------------

```YAML
# Directory .vimrc would be created
vimrc_dir: /root
```

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
---
- hosts: all
  become: true
  roles:
    - vim
```

License
-------

BSD
