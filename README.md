Role Name
=========

Transfer cpanel backup to server

Role Variables
--------------

- backup_url: BACKUP_DIRECT_URL
- domain: example.com

Dependencies
------------

- kbrebanov.zip
- kbrebanov.unzip
- geerlingguy.mysql
- geerlingguy.apache
- geerlingguy.php
- geerlingguy.php-mysql

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ahmadrezaei.cpanel_backup_transfer, domain: example.com, backup_url: some_url }

License
-------

BSD / MIT
