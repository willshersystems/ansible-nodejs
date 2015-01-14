[![Build Status](https://travis-ci.org/willshersystems/ansible-nodejs.svg?branch=master)](https://travis-ci.org/willshersystems/ansible-nodejs)
[![Ansible Galaxy](http://img.shields.io/badge/galaxy-willshersystems.nodejs-660198.svg?style=flat)](https://galaxy.ansible.com/list#/roles/2580)

nodejs
======

Install Node.js following the current official package based installation guide.

Requirements
------------

Works on current Debian and Ubuntu releases.

Role Variables
--------------

None

Dependencies
------------

- willshersystems.apt

Example Playbook
----------------

```yaml
    - hosts: servers
      roles: willshersystems.nodejs
```

License
-------

LGPLv3

Author Information
------------------

Matt Willsher <matt@willsher.systems>

&copy; 2015 Willsher Systems
