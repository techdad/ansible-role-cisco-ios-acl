Cisco ACL Role
==============

A fairly simple role to apply ACLs to interfaces on a Cisco IOS device.

This role is designed to be applicable mainly to ACLs applies to Vlan SVI interfaces on a L3 switch. And it follows a fairly specific naming convention for the ACLs.

It is intended to eventually allow overrides of everything with appropriate variables, but in the mean time, should still be fairly adaptable in a fork if necessary.

Requirements
------------

None.

Role Variables
--------------

TBD

Dependencies
------------


Example Playbook
----------------

TBD...

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

Apache 2.0

Author Information
------------------

AFRINIC: Daniel Shaw <daniel@afrinic.net>

