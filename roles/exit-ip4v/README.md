exit-ipv4
=========================

A role to setup up a OpenVPN, GRE or IPIP connection as exit.


Role Variables
------------------------

### GRE oExit

    exit_ipv4: Tunnel mode (GRE)
    exit_ipv4_address
    exit_ipv4_address_global
    exit_ipv4_address_peer
    exit_ipv4_local
    exit_ipv4_remote

Usage
------------------------

    - hosts: servers
      roles:
         - { role: exit-ipv4, exit_ipv4: "gre" }


License
------------------------

GPLv3
