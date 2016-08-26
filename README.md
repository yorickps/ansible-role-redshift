gvillalta99.redshift
===============

[![Build Status](https://travis-ci.org/ymajik/ansible-redshift.svg?branch=master)](https://travis-ci.org/ymajik/ansible-redshift)

Install [redshift](http://jonls.dk/redshift/).


Installation
------------

`$ ansible-galaxy install gvillalta99.redshift`

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: redshift
          redshift:
            location:
              latitude: "40"
              longitude: "5"
            gui_enabled: false


Requirements
------------

- Tested on Fedora 23,24 & Ubuntu 14.04,16.04


License
-------

BSD
