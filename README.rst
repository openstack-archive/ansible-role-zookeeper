======================
ansible-role-zookeeper
======================

Ansible role to manage ZooKeeper

* License: Apache License, Version 2.0
* Documentation: https://ansible-role-zookeeper.readthedocs.org
* Source: https://git.openstack.org/cgit/openstack/ansible-role-zookeeper
* Bugs: https://bugs.launchpad.net/ansible-role-zookeeper

Description
-----------

Virtualenv is a tool to create isolated Python environments.

Requirements
------------

Packages
~~~~~~~~

Package repository index files should be up to date before using this role, we
do not manage them.

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

.. code-block:: yaml

    - name: Install zookeeper
      hosts: all
      roles:
        - ansible-role-zookeeper
