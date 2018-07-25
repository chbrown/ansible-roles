## Installation

Via environment variable:

    export ANSIBLE_ROLES_PATH=~/github/ansible-roles

Via [GNU Stow](https://www.gnu.org/software/stow/):

    mkdir -p ~/.ansible/roles
    stow --ignore='README.md' -t ~/.ansible/roles .


## Documentation

- [Ansible Docs » Roles](https://docs.ansible.com/ansible/latest/user_guide/playbooks_reuse_roles.html)


## License

Copyright 2017–2018 Christopher Brown.
[MIT Licensed](https://chbrown.github.io/licenses/MIT/#2017-2018).
