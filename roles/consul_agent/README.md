consul_agent
=========

Configures the instance as a consul agent.

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

- consul_base

Example Playbook
----------------


    - hosts: servers
      roles:
         - consul_agent

License
-------

MIT

Author Information
------------------

Niels Albers (niels.albers@ordina.nl)
