# Ansible Role: Template

[![CI](https://github.com/netr0m/ansible-role-template/workflows/CI/badge.svg?event=push)](https://github.com/netr0m/ansible-role-template/actions?query=workflow%3ACI)

Describe the purpose of this role

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see [`defaults/main.yml`](./defaults/main.yml))

```yml
example_var: "some string"
```
*An example variable*

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  vars_files:
    - vars/main.yml
  roles:
    - { role: netr0m.ansible-role-template }
```

## License

[MIT](./LICENSE)

## Author Information

This role was created in 2022 by [netr0m](https://github.com/netr0m)
