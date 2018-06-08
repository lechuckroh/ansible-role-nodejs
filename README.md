# Ansible role `node.js`

An ansible role for node.js

Tested under:
* CentOS 7.4

## Requirements

No requirements

## Role Variables

| Variable               | Default | Comments                |
|:-----------------------|:--------|:------------------------|
| `nodejs_version`       | `10`    |                         |

## Dependencies

No dependencies

## Example Playbook

```yaml
---
- name: example
  hosts: all
  become: true
  vars:
    nodejs_version: 10
  roles:
  - lechuckroh.nodejs
```

## License
MIT
