# Ansible Managed Workspace

Workspace configuration using the ansible role: tnaglo.unix_home_setup

## Dependencies

- ansible (if used to install on localhost)

## Usage

To install the user and his configure his environment on the local machine you first have to install the requirements:

@todo change the functionality and readme accordingly (add parametrized install script).

`ansible-galaxy install -r roles/requirements.yml`

If the user does not exist yet, run:

`ansible-playbook -i "localhost," -c local create-user.yml -b -K`

Next run:

`ansible-playbook -i "localhost," -c local setup-home.yml`
