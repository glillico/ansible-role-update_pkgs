# Ansible Role : update_pkgs

[![molecule](https://github.com/glillico/ansible-role-update_pkgs/workflows/molecule/badge.svg)](https://github.com/glillico/ansible-role-update_pkgs/actions?query=workflow%3Amolecule)

This role updates all installed packages to the latest versions. Dependencies are also installed if requried.

## Requirements

None

## Role Variables

None

## Dependencies

None

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.update_pkgs

## License

MIT

## Author Information

This role was created in 2020 by Graham Lillico. (Inspired by [geerlingguy/ansible-role-security](https://github.com/geerlingguy/ansible-role-security))
