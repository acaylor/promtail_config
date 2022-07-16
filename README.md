Promtail Config
=========

This role will install and configure promtail agent on debian based linux distributions.

Requirements
------------

Unzip is required on systems, and the role will attempt to install.

Role Variables
--------------

- loki_url: Required variable to point your systems to your loki deployment

Dependencies
------------

no other dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: promtail_config, loki_url: loki.url }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
