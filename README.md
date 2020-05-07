[![](https://github.com/ansible-roles-matsumura/vim/workflows/yamllint/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Ayamllint)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/ansible-playbook/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Aansible-playbook)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/ansible-lint/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3Aansible-lint)
[![](https://github.com/ansible-roles-matsumura/vim/workflows/trailing%20whitespace/badge.svg)](https://github.com/ansible-roles-matsumura/vim/actions?query=workflow%3A%22trailing+whitespace%22)

Role Description
=========

Installs vim for CentOS7.

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
