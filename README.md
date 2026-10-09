# Ansible Role: wireguard_server

[![Ansible Lint](https://github.com/leberkaslabs/ansible-role-wireguard_server/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/leberkaslabs/ansible-role-wireguard_server/actions/workflows/ansible-lint.yml)

Setup WireGuard server.

## Prerequisites

- Ensure you have Ansible installed (e.g. `pip3 install ansible`)
- **Development**: Install the pip packages listed in [requirements.txt](requirements.txt)

## Role Variables

The default values for the variables are set in [defaults/main.yml](defaults/main.yml)

```yaml
- hosts: all
  roles:
    - role: leberkaslabs.wireguard_server
```

## License

Copyright (c) 2026 Niclas Spreng
