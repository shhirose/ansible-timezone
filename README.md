# shhirose.timezone

[![Github](https://img.shields.io/badge/github-shhirose%2Fansible--timezone-brightgreen.svg)](https://github.com/shhirose/ansible-timezone)
[![Ansible galaxy](https://img.shields.io/badge/ansible--galaxy-timezone-brightgreen.svg)](https://galaxy.ansible.com/shhirose/timezone/)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

This is Ansible role for timezone setting for RedHat Enterprise Linux.

## Requirements

None

## Role Variables

```
shhirose_timezone: "UTC"
```

## Variable parameters

| key | required | default | type | values | notes |
| --- | --- | --- | --- | --- | --- |
| shhirose_timezone | no | UTC | string | Asia/Tokyo | timezone value |

## Dependencies

None

## Example Playbook

```
- hosts: servers
  become: yes
  roles:
    - shhirose.timezone
  vars:
    shhirose_timezone: "Asia/Tokyo"
```

## License

MIT
