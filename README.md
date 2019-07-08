Java OpenJDK role
=============

A simple Ansible role for installing Java OpenJDK.


Defaults
--------

Just one:

```
openjdk_version: 11
```

Example playbook
----------------

```
- name: Install OpenJDK
  hosts: webservers

  roles:
    - role: libre_ops.open_jdk
```
