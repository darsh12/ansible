multiple_users
=========

This role installs packages that are required by multiple-users
- oh-my-zsh
- vim-plug
- tpm
- dotfiles


Role Variables
--------------
```yaml
users:
 - username: root
```


Dependencies
------------

- gantsign.oh-my-zsh

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:
```yaml
- hosts: multiple_users
  roles:
    - role: multiple_users
      vars:
        users:
          - username: root
          - username: user1
        

```



License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
