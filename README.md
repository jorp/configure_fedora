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

- add tags
- remove data and add empty defaults for modularity
    - everything is a bit messy and just dumped in var/main.yml for now
- more error handling
