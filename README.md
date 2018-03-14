OpenJDK JDK
===========

Installs OpenJDK JDK packages

Requirements
------------

- none

Role Variables
--------------

| Variable | Default | Definition |
|----------|---------|------------|
| openjdk_jdk_version | 8 | Version of the JDK to install |

Dependencies
------------

- none

Example Playbook
----------------

```
- hosts:
    - servers
  roles:
    - rgibert.openjdk-jdk
```

License
-------

GPLv3

Author Information
------------------

Richard Gibert
<richard@gibert.ca>
