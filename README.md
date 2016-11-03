New Relic Sysmond
=========
This role installs [Tmate-slave](https://github.com/tmate-io/tmate-slave) service and ensure its up and running.

Requirements
------------
None

Role Variables
--------------

Install location of binary:

    tmate_slave_prefix: /usr/local/bin

Location of ssh keys:

    tmate_slave_keys: /etc/tmate-slave-keys

Port tmate-slave should use:

    tmate_slave_port: 2222

Hostname:

    tmate_slave_host: localhost

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-tmate-slave }

License
-------

MIT
