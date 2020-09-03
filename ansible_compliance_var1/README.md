Role Name
=========

The role is simple number of playbooks which is comparing two files with using diff

Requirements
------------

Required pre-configured host with diff and web-server to share reports

Role Variables
--------------
There is no variables on the first role ( VAR1 ) - that is straigtforward role with pre-defined parameters

Dependencies
------------

No Deps

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ansible_compliance_var1 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
