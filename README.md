andrewrothstein.dumb_init
===========================
![Build Status](https://github.com/andrewrothstein/ansible-dumb_init/actions/workflows/build.yml/badge.svg)

Installs [dumb-init](https://github.com/Yelp/dumb-init).


Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.dumb_init
```

License
-------

MIT

Author Information
------------------
* Vishal Shah <vishal.shah@nyu.edu>
* Andrew Rothstein <andrew.rothstein@gmail.com>
