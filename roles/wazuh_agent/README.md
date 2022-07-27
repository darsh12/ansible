wazuh_agent
=========

Installs wazuh-agent on defined hosts

Role Variables
--------------
- wazuh_manager_ip
- wazuh_manager_password
- wazuh_agent_group

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: servers
  roles:
     - role: wazuh_agent
  vars:
    wazuh_manager_ip: localhost
    wazuh_manager_password: registerpassword
    wazuh_agent_group: group
```


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
