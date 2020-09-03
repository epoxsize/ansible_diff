Role Name
=========

The role is simple number of playbooks which is comparing two files with using diff

Requirements
------------

Required pre-configured host with diff and web-server to share reports

Role Variables
--------------
There is no variables on the first role ( VAR1 ) - that is straigtforward role with pre-defined parameters
There is severar variables as in example ( VAR2 ) - that is straigtforward role with pre-defined parameters

Example :

configuration_id:
  nginx:
    src_config: 'nginx.conf'
    destination_config: '/tmp/nginx.conf'
    file_mode: '0777'
  apache:
    src_config: 'apache.conf'
    destination_config: '/tmp/apache.conf'
    file_mode: '0777'
  
webdir_config: /nginx



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
