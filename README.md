aptly
=========

Installs and configures aptly.

Requirements
------------

None.

Role Variables
--------------


| Variable Name | Default Value | Description |
--------------- |---------------|--------------
---
`aptly_user` | `aptly` | Name of the aplty user
`aptly_configuration` | `{}` | Aptly configuration, will be converted to JSON and written to `~/.aptly.conf`

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - role: aptly
           aptly_user: myuser

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
