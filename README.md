# General information

- To run the playbook you need SSH access to the corresponding inventory hosts declared in the hosts file

Playbook launch command template:

`ansible-playbook <playbook_name>.yml --diff`

## Available playbooks

| Name of the playbook | Playbook purpose                                       | Roles     |
|----------------------|--------------------------------------------------------|-----------|
| add_user             | Adds users and their authorized keys to remote servers | add_user  |