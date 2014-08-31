Ansible Role - Gulp
====================

A gulp role to install gulp on elao symfony standard vagrant box


Requirements
------------

This role only run on elao symfony standard vagrant box. See https://vagrantcloud.com/elao/symfony-standard-debian


Role Variables
--------------

    elao_gulp_version: '>0'  # Gulp version


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: elao.gulp }

License
-------

MIT


Author Information
------------------

http://www.elao.com/
