Chrome Broswer Role
=========

Ansible role to install Google Chrome (Stable) for dnf or apt based systems.

This was designed as part of a desktop provisioning playbooks found here <https://github.com/billwheatley/provision-desktop>

Requirements
------------

- A distribution with `dnf` or `apt`

Role Variables
--------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- name: My Playbook
  hosts: desktop
  roles:
    - role: chrome-role
```

License
-------

GPLv2

Author Information
------------------

Contact via [Github](https://github.com/billwheatley/)
