[![Build Status](https://travis-ci.org/wtanaka/ansible-role-screenruler.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-screenruler)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-screenruler.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-screenruler)

wtanaka.screenruler
===================

This ansible role installs screenruler

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.screenruler

### `screenruler_should_shortcircuit`

Default: True

When True, this role short-circuits itself if a "screenruler" is
already in the path

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
