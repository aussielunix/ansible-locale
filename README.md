# Ansible Role - Locale

![Build Status](https://circleci.com/gh/aussielunix/ansible-locale/tree/master.svg?style=shield&circle-token=af1c34bff05f50824300dc8b436b9e0a6bd564da "CircleCI Build Status")

This role will ensure that the various places you need to set the locale are all set to the same thing.

## Requirements

None

## Role Variables

```
aussielunix_locale: en_AU.UTF-8
```

## Dependencies

None

## Example Playbook

    - hosts: all
      roles:
         - { role: aussielunix.locale, aussielunix_locale: en_AU.UTF-8 }

## Hacking

There is an included Vagrant setup for hacking on this module.  

```
cd tests
source .hack.sh
vagrant up
ansible-playbook test.yml
...
vagrant destroy
vagrant up
ansible-playbook test.yml -vvvv
...
```

## License

BSD

## Author Information

Mick Pollard
@aussielunix (twitter, gmail, github, linkedin)
