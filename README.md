gvillalta99.redshift
===============

Install redshift.


Installation
------------

`$ ansible-galaxy install gvillalta99.redshift`

Dependencies
------------

On Fedora:

  - redshift


Example Playbook
----------------

    - hosts: servers
      roles:
        - role: redshift
          redshift:
            location:
              latitude: "40"
              longitude: "5"


Requirements
------------

- Tested on Fedora 19

License
-------

BSD
