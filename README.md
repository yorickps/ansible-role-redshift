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
            latitude: "-22"
            longitude: "-45"


Requirements
------------

- Tested on Fedora 19

License
-------

BSD
