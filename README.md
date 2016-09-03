mamercad.icinga2-server
=======================

Stands up Icinga2 on RHEL/CentOS (rough first draft)

Warnings
--------

* The role puts SELinux into permissive mode and _enables_ firewalld
* IcingaWeb Director Installtion is Alpha

Requirements
------------

* EPEL 7 (for `python-pip` providing the `firewall` package)

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
        - mamercad.epel
        - mamercad.icinga2-server

Usage
_____

After installation, visit `/icingaweb` and log with `icingaadmin` and standard password `icingaadmin`. The password (via hash), can be changed in `vars/main.yml`.

License
-------

GPLv3

Author Information
------------------

Mark Mercado <mamercad@umflint.edu>
Merlin Blom
