Role Name
=========

This role installs the packages necessary to get a new server up and running. It also updates the packages.
Installed packages:

- fd-find
- ripgrep
- bat
- fzf
- powerline-status
- jq
  

- software-properties-common
- python3-pip
- fonts-powerline
- curl
- unzip
- wget
- xsel
- tmux
- vim
- htop
- tmuxinator


Role Variables
--------------

None

Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: common-packages

License
-------

BSD/MIT
