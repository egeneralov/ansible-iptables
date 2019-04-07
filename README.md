egeneralov.iptables
===================

Basic iptables managment via ansible

Variables
---------

- **manage_iptables**: `false`

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: egeneralov.iptables, manage_iptables: true }

License
-------

MIT

Author Information
------------------

Eduard Generalov <eduard@generalov.net>
