andrewrothstein.ship
=========
![Build Status](https://github.com/andrewrothstein/ansible-ship/actions/workflows/build.yml/badge.svg)

Installs ReplicatedHQ's [ship](https://www.replicated.com/ship/)

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
    - andrewrothstein.ship
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
