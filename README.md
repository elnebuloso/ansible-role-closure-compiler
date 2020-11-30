# Ansible Role - Google Closure Compiler

![abandoned](https://img.shields.io/badge/project-abandoned-red)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16
- centos6
- centos7

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-closure-compiler/blob/master/defaults/main.yml)

```
closure_compiler_version: "20170626"
```

## Example Playbook

```
- hosts: localhost
  roles:
    - role: elnebuloso.closure-compiler
```

## Dependencies

None.

##  License

MIT

##  Author Information

This role was created in 2016 by [elnebuloso](https://github.com/elnebuloso/)