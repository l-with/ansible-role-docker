# Ansible Role Docker

Installs Docker

## Variables

### `docker_manipulate_iptables_rules`: `yes`

if docker can manipulate iptable rules

## Role Variables

<!-- markdownlint-disable MD033 -->
| group | variable | default | description |
| --- | --- | ---| --- |
| install | docker_manipulate_iptables_rules | `true` | if docker can manipulate iptable rules |
| install | docker_hold_packages_versions | `false` | if the packages versions of docker should be hold to prevent updates |
<!-- markdownlint-enable MD033 -->
