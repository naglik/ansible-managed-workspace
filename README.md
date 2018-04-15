# Ansible Managed Workspace
Workspace configuration using the ansible role: naglik.unix-user-env

# Dependencies
- ansible

# Usage
To install the user and his configure his environment on the local machine you first have to install the requirements:

@todo change the functionality and readme accordingly (add parametrized install script).

`ansible-galaxy install -r requirements.yml`

and then run:

`ansible-playbook -i "localhost," -c local site.yml`
