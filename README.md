Role Name
=========

Simple lighthouse role.

Role Variables
--------------
F: You can change lighthouse directory.

`lighthouse_dir: "/var/www/html/lighthouse"`

Example Playbook
----------------

    - name: Install lighthouse
      hosts: server
      vars:
        - lighthouse_dir: "/var/www/html/lighthouse"
      roles:
        - ansible-lighthouse

License
-------

BSD

Author Information
------------------

Role by Dimsunv.

Dear contributors, thank you.