configure_fedora
=========

A brief description of the role goes here.


Requirements
------------
`python3-psutil`


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: jorp.configure_fedora, become: yes }


TODO
----

- ~~Fix `become` in `gnome.yml`~~
- add tags
- remove data and add empty defaults for modularity
- more error handling
