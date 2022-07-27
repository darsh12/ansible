mail
=========

This role setup a postfix based relay server to enable sending mail from host


Role Variables
--------------
- smtp_address: smtp.example.com
- relay_port: 465
- mail_relay_email: email@example.com
- mail_relay_password: password


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: servers
  roles:
     - role: mail
  vars:
    smtp_address: smtp.example.com
    relay_port: 465
    mail_relay_email: email@example.com
    mail_relay_password: password
```
   

License
-------

BSD/MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
