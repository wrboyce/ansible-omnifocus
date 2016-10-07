wrboyce.omnifocus
=================

[![Build Status](https://travis-ci.org/wrboyce/ansible-omnifocus.svg)](https://travis-ci.org/wrboyce/ansible-omnifocus)

Install & Configure OmniFocus.app

Requirements
------------

* [Homebrew](http://brew.sh)

Role Variables
--------------

`omnifocus_sync_user` defaults to `user_username`.
`omnifocus_sync_url` defaults to `https://{{ omnifocus_sync_user }}@sync.omnigroup.com/{{ omnifocus_sync_user }}/OmniFocus.ofocus$encrypted`.

Example Playbook
----------------

    - hosts: macos-workstations
      roles:
         - wrboyce.omnifocus

License
-------

Apache 2.0