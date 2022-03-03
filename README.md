[![CircleCI](https://circleci.com/gh/ansible-roles-mamono210/vim/tree/main.svg?style=svg)](https://circleci.com/gh/ansible-roles-mamono210/vim/tree/main)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/build/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Abuild)

Role Description
=========

Installs vim for CentOS7/Stream8.

Requirements
------------

None

Role Variables
--------------

```YAML
# Directory where the .vimrc file would be created
vimrc_dir: /root

# Name of the group of the .vimrc file
vimrc_group: root

# The permissions the .vimrc file
vimrc_mode: '0644'

# Name of the user of the .vimrc file
vimrc_owner: root
```

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
