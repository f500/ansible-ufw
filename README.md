Ufw
========

Install UWF (Uncomplicated Firewall)

Requirements
------------

Debian Wheezy with the package python-pycurl and python-software-properties installed.

Example Playbook
-------------------------

    - hosts: servers
      roles:
         - { role: f500.ufw }

License
-------

LGPL.

Author Information
------------------

Jasper N. Brouwer, jasper@nerdsweide.nl

Ramon de la Fuente, ramon@delafuente.nl
