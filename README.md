# Ansible Role: Cisco IOS ACLs

An Ansible role to apply extended ACLs to interfaces on a Cisco IOS device.

This role is intended only to manage Cisco IOS extended access control lists, not an entire configuration.

The primary use case it's initially developed for is to manage ACLs applicable to vlan SVI interfaces on L3 switches and/or physical router interfaces. It supports creating and updating the ACLs, but may not initially support applying them to the relevant interface(s).

## Role Variables

TBD

## Example Playbook

TBD...

    ---
    - hosts: [ "ios-devices" ]
      gather_facts: no
      connection: local

      roles:
        - { role: cisco-ios-acl, tags: ['cisco', 'acl'] }

      vars:
        cisco_userid: "some_userid"
        cisco_passwd: "the_users_password"
        cisco_enable: "the_enable_secret"

## License

Apache 2.0

## Author Information

Daniel Shaw <daniel@afrinic.net>
