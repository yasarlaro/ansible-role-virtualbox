Role Name
=========

Installs VirtualBox on CentOS 7 or CentOS 8.

Requirements
------------

Host OS CPU has to support virtualization. Role also performs a check against it and fails it the requirement is not met

Role Variables
--------------

Role has only one variable: `virtualbox_version`. Please change it with the version you would like to use.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: yasarlaro.virtualbox }

License
-------

MIT

Author Information
------------------

Onur Yasarlar
