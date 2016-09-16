psptoolchain
============

[![Build Status](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain.png?branch=master)](https://travis-ci.org/nabilbendafi/ansible-role-psptoolchain)

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
