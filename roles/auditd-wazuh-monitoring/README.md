Role Name
=========

This role installed auditd and sets up the required rule to monitor root and malicious commands which is then sent to a wazuh server

Requirements
------------

Ensure that the host is not a lxc instance

Role Variables
--------------

none

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
     - role: auditd-wazuh-monitoring
```

License
-------

BSD/MIT
