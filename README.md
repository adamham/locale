[![Build Status](https://travis-ci.org/adamham/locale.svg?branch=master)](https://travis-ci.org/adamham/locale)

Locale
=========

Update the locale on a machine

Tested using Ansible 2.1.2 on:

CentOS 7
Debian Jessie
Ubuntu Trusty

Requirements
------------

Ansible 2+

Role Variables
--------------

```yaml
timezone_zone: UTC
```


Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      become: true
      roles:
         - locale

License
-------

MIT
