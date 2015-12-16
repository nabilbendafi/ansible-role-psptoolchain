psptoolchain
============

[![TravisCI Build Status](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain)
[![Shippable Build Status](https://img.shields.io/shippable/566987de1895ca44744e8638/master.svg)](https://app.shippable.com/projects/566987de1895ca44744e8638)
[![SemaphoreCI Build Status](https://semaphoreci.com/api/v1/projects/98918861-7ce3-4906-95a0-bbcd1b208514/637149/badge.svg)](https://semaphoreci.com/nabilbendafi/ansible-role-psptoolchain)

This role installs and configures the open-source [psptoolchain](https://github.com/pspdev/psptoolchain) for PSP homebrew development.

Installation
------------

```
$ ansible-galaxy install nabilbendafi.psptoolchain
```

```
# psptoolchain.yml
- hosts: localhost
  roles:
    - psptoolchain
```

```
$ ansible-playbook psptoolchain.yml
```

Dependencies
------------

None

License
-------

[MIT](LICENSE.txt)

Author Information
------------------

[Nabil Bendafi](https://github.com/nabilbendafi)
