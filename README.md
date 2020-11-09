Role Name
=========

Ansible role used to install teamcity server as a service.

Requirements
------------

None.

Role Variables
--------------

The following variables can be overridden to customize service installation

- teamcity_version: "2020.1.5"
- service_path: "/var/www"
- archive_path: "/tmp"
- server_archive: "TeamCity-{{ teamcity_version }}.tar.gz"
- server_archive_path: "{{ archive_path }}/{{ server_archive }}"
- teamcity_user: teamcity
- teamcity_group: teamcity

Dependencies
------------

None.

Example Playbook
----------------

TODO

License
-------

GPL

Author Information
------------------

TODO
