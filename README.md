yorickps.redshift
===============

[![Build Status](https://travis-ci.org/ymajik/ansible-role-redshift.svg?branch=master)](https://travis-ci.org/ymajik/ansible-role-redshift)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-redshift-blue.svg?style=flat)](https://galaxy.ansible.com/yorickps/redshift/)

Install [redshift](http://jonls.dk/redshift/).


Installation
------------

`$ ansible-galaxy install yorickps.redshift`

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

- Tested on Fedora 23,24 & Ubuntu 14.04,16.04, Debian 8.5


License
-------

BSD
