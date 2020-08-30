SSH
=========

Install and configure SSH services

Requirements
------------

None

Role Variables
--------------

* allow_password_authentification (default: false)
* ssh_user (optional)
* ssh_public_key (optional)
* set_sudo (default: true)
* ssh_sudo_rule (default: "ALL=(ALL) NOPASSWD: ALL")

Dependencies
------------

None

Example Playbook
----------------

    - hosts: localhost
      roles:
        - role: ssh
          ssh_user: ansible
          ssh_public_key: ansible_key.pub

License
-------

BSD

Author Information
------------------

arnaud@lecann.com
