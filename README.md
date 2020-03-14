# Ansible Managed Workspace

Workspace configuration using the ansible role: tnaglo.ansible_role_unix_user_env

## ToDo

- [ ] Switch to new role (TDB) instead of [tnaglo.ansible_role_unix_user_env](https://galaxy.ansible.com/tnaglo/ansible_role_unix_user_env)

## Dependencies

- ansible (if used to install on localhost)

## Usage

To install the user and his configure his environment on the local machine you first have to install the requirements:

@todo change the functionality and readme accordingly (add parametrized install script).

`ansible-galaxy install -r roles/requirements.yml`

and then run:

`ansible-playbook -i "localhost," -c local site.yml --ask-become-pass`
