Ansible Role - phpPgAdmin
=========================

A phpPgAdmin role to install phpPgAdmin on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Variables
--------------

    elao_phppgadmin_host: phppgadmin  # phpPgAdmin host


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.postgresql-phppgadmin }


License
-------

MIT


Author Information
------------------

http://www.elao.com/
