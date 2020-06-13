[![](https://github.com/ansible-roles-matsumura/vim/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/molecule/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Amolecule)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3A%22trailing+whitespace%22)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Ayamllint)

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
