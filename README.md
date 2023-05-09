# Ansible Role : update_pkgs

[![CI](https://github.com/glillico/ansible-role-update_pkgs/workflows/CI/badge.svg)](https://github.com/glillico/ansible-role-update_pkgs/actions?query=workflow%3ACI)

This role updates all installed packages to the latest versions. Dependencies are also installed if requried.

## Requirements

None

## Role Variables

|Variable|Description|
|---|:---|
|upk_server_reboot|If set to `true` a reboot check will be carried out, if one is requried it will be performed.|

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

Created in 2020 by Graham Lillico. (Inspired by [geerlingguy/ansible-role-security](https://github.com/geerlingguy/ansible-role-security))
