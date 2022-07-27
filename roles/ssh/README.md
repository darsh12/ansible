Ansible-Role: ssh
=========
Configure a default secure sshd_config file

Role Variables
--------------
- ssh_port: 22

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: ssh
  vars:
    ssh_port: 22
```
License
-------

MIT/BSD

Author Information
------------------

Role created in 2022