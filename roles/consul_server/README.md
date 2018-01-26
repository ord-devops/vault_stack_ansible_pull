consul_server
=========

Configures the instance as a consul server in a cluster using AWS autodiscovery.

Requirements
------------

- boto
- boto3
- awscli

Role Variables
--------------

none

Dependencies
------------

- consul-agent

Example Playbook
----------------


    - hosts: servers
      roles:
         - consul_server

License
-------

MIT

Author Information
------------------

Niels Albers (niels.albers@ordina.nl)
