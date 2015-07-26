Debian-Sharedance
=================

Sharedance is a high-performance server to centralize ephemeral key/data pairs on remote hosts, designed to share caches and sessions between a pool of web servers.

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

sharedance_version: "0.6"

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: loranger.debian-sharedance, sharedance_version: "0.6" }

Tasks
-----

  - Install [Sharedance](http://www.pureftpd.org/project/sharedance) server
  - Register service

License
-------

BSD