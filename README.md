Evergreen-ILS SIP Server
=========

This role will install and configure the SIP server that comes with Evergreen-ILS. This is used for integration with services like Overdrive and certain self-checks.

Requirements
------------

This role presumes you have a working Evergreen-ILS installation. The variable names and defaults match up with a normal installation so may or may not need changing.

Role Variables
--------------



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: evergreen-application-servers
      roles:
         - { role: aadl.evergreenils-sip, become: true }

License
-------

GPLv3