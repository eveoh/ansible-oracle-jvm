Oracle JVM role for Ansible
===========================

Installs Oracle JVM 8 on Debian and Ubuntu from the [webupd8team PPA](http://www.webupd8.org/2012/09/install-oracle-java-8-in-ubuntu-via-ppa.html). Also installs the Java Cryptography Extension (JCE) Unlimited Strength Jurisdiction Policy Files. 

Requirements
------------

By using this Ansible role you agree applicable Oracle licenses and terms.

Role Variables
--------------

None currently.

Dependencies
------------

None currently.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: praseodym.oracle-jvm }

License
-------

MIT

Author Information
------------------

[Mark Janssen](http://www.praseodym.net/)
