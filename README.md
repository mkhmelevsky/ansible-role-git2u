# Role Name

This Ansible role is intended to install Git2U on RHEL/CentOS 7 host

## Requirements

- Hosts should be bootstrapped for ansible usage (have python,...)
- Ansible user can obtain root privileges, eg `become: yes`

## Role Variables

None.

## Dependencies

None.

## Example Playbook

```yaml
---
  - name: Apply role ansible-role-git2u to every host in group 'all'
    hosts: all
    roles:
      - role: ansible-role-git2u
```

## License

MIT

## Author Information

Author:
  - Max Khmelevsky <max.khmelevsky@yandex.ru>
