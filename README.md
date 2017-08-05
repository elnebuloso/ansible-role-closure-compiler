# Ansible Role - closure-compiler for Linux Server

[![Build Status](https://travis-ci.org/elnebuloso/ansible-role-closure-compiler.svg?branch=master)](https://travis-ci.org/elnebuloso/ansible-role-closure-compiler)

## Requirements

This role requires Ansible 2.0 or higher, and platform requirements are listed in the metadata file.

## Supported Distributions

- ubuntu14
- ubuntu16
- centos6
- centos7

## Role Variables

- [`defaults/main.yml`](https://github.com/elnebuloso/ansible-role-php7/blob/master/defaults/main.yml)

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