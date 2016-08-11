mamercad.icinga2-server
=======================

Stands up Icinga2 on RHEL/CentOS (rough first draft)

Warnings
--------

The role puts SELinux into permissive mode and disabled firewalld
IcingaWeb Director Installtion is Alpha

Requirements
------------

None

Role Variables
--------------

See the example inventory below, as well as vars/main.yml

Dependencies
------------

None

Example Playbook
----------------

    - hosts:
        - icinga2
      roles:
        - mamercad.icinga2-server

Usage
_____

After Installation go to /icingaweb and log with icingaadmin and standard password  icingaadmin.

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
Merlin Blom 
