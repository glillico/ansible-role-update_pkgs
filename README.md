# Ansible Role : Update Packages

This role updates all installed packages to the latest versions. Dependencies are also installed if requried.

## Requirements

None

## Role Variables

None

##Dependencies

None

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - glillico.update_pkgs

## License

MIT

## Author Information

This role was created in 2020 by Graham Lillico.