Role Name
=========

This role creates a simple fileserver and shares a folder

Requirements
------------

The server has to be [domain joined](https://github.com/ait-testbed/atb-ansible-msclient) to properly assign permission for the shared drive.


Role Variables
--------------
none

Dependencies
------------

pywinrm

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: atb-ansible-winfileserver

License
-------

MIT

Author Information
------------------

Sebahattin Sahin
