Entia non sunt multiplicanda praeter necessitatem

stattools - This is the role which installs my favorite performance tools:

1. atop
2. iotop
3. sysdig

Role still in development.

Requirements
------------
At this moment it was tested on Ubuntu 14.04 but it should work on all Debian-like systems.
RedHat family systems will be added.

Role Variables
--------------
All variables defined in defaults/main.yml

Dependencies
------------
None

Example Playbook
----------------
- hosts: servers
  roles:
    - stattools


License
-------
GPLv2

Author Information
------------------
@kapekto1
