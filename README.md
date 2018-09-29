Role Name
=========

Installation of Java runtimes than any self-respecting JVM developer loves and needs.

Requirements
------------

TODO

Role Variables
--------------

* jvm_azul_jdk_install: false
* jvm_azul_jdk_build: 8.17.0.3
* jvm_azul_jdk_version: 8.0.102
* jvm_azul_jdk_link_destination: azul-jdk-8
* jdk_azul_jdk_11_install: true
* jdk_azul_jdk_11_build: 11.1+23-ea
* jdk_azul_jdk_11_link_destination: azul-jdk-11


Dependencies
------------

* kurron.base

Example Playbook
----------------

```
- hosts: servers
  roles:
      - { role: kurron.jvm-developer, jvm_azul_jdk_install: true, jdk_azul_jdk_11_install: false }
```

License
-------

This project is licensed under the [Apache License Version 2.0, January 2004](http://www.apache.org/licenses/).

Author Information
------------------

[Author's website](http://jvmguy.com/).
