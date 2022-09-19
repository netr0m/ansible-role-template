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

## Development
This project uses [pre-commit](https://pre-commit.com/).

Currently, there are three hooks:
- [ansible-lint](https://pypi.org/project/ansible-lint/)
- [yamllint](https://pypi.org/project/yamllint/)
- [encryption-check](./scripts/encryption-check.sh)

To run `pre-commit` manually, run `pre-commit run -a`

### Requirements
To run pre-commit, you need three things:
1. A virtual environment in the parent directory of this repository
  - `$ python3 -m venv ../.venv`
  - `$ source ../.venv/bin/activate`
2. The Python dependencies (see [requirements.txt](./requirements.txt))
  - `$ pip install -r requirements.txt`
3. Pre-commit hooks installed
  - `$ pre-commit install`

## License

[MIT](./LICENSE)

## Author Information

This role was created in 2022 by [netr0m](https://github.com/netr0m)
