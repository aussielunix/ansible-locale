# Ansible Role - Locale

This role will ensure that the various places you need to set the locale are all set to the same thing.

## Requirements

None

Role Variables
--------------

  locale: en_AU.UTF-8

Dependencies
------------

None

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: aussielunix.locale, locale: en_AU.UTF-8 }

License
-------

BSD

Author Information
------------------

Mick Pollard
@aussielunix