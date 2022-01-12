# Ansible Role Docker

![Build Status](https://github.com/6nsh/ansible-role-docker/actions/workflows/ansible-galaxy-ci.yml/badge.svg)

This role helps to install and configure Docker to Debian (buster/bullseye).

Requirements
------------

This role requires Ansible 2.9 or higher.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: 6nsh.docker, tags: docker }

License
-------

MIT

Author Information
------------------

This role was created by Artem Kasianchuk.
