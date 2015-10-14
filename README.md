WARNING: This role is no longer maintained !!!
==============================================

You are strongly encouraged to switch to the new roles stack on https://github.com/ElaoInfra
--------------------------------------------------------------------------------------------

By the way, this role will remain available on https://github.com/ElaoLegacy
----------------------------------------------------------------------------


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
