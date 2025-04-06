# Ansible Role: mailbox

[![Lint](https://github.com/dcjulian29/ansible-role-mailbox/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-mailbox/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-mailbox.svg)](https://github.com/dcjulian29/ansible-role-mailbox/issues)

This an Ansible role to to install and configure a secure mailbox server based on postfix and dovcot

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.mailbox
  src: https://github.com/dcjulian29/ansible-role-mailbox.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

- None
