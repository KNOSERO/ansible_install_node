# Ansible Install Node
Script for installing node in Ansible


## Example

```yaml
- name: Install Node.js
  hosts: localhost
  become: true
  vars:
    node_version: "20" 
```