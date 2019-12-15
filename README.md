This playbook installs Vim enhanced on CentOS7.

## Install Vim enhanced 

Change to root and execute commands below.

```
ansible-playbook -i localhost, -c local install.yml
```

## Customized .vimrc

'.vimrc' file is placed in 'roles/templates/.vimrc'. Change the file 
as necessary.
