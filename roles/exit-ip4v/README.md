exit-ipv4
=========================

A role to setup up a gre Connection


Role Variables
------------------------

### GRE Exit

    exit_mode           Type GR
    exit_remote_v4
    exit_local_v4
    exit_local_v6
    system_localv4


Usage
------------------------

    - hosts: servers
      roles:
         - { role: exit-ipv4, exit_mode: "gre" }


License
------------------------

GPLv3
