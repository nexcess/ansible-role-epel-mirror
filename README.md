# Ansible Role: EPEL Mirror

Installs the EPEL mirroring role

## Requirements

None.

## Role Variables

See `defaults/main.yml`.

## Dependencies

nexcess.mirror

## Add to Requirements

    - src: https://github.com/nexcess/ansible-role-epel-mirror.git
      name: nexcess.epel-mirror

## Example Playbook

    - hosts: servers
      roles:
        - nexcess.epel-mirror

## License

MIT / BSD
