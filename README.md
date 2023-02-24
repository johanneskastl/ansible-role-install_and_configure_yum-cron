![Ansible Lint](https://github.com/johanneskastl/ansible-role-install_and_configure_yum-cron/workflows/Ansible%20Lint/badge.svg)

install_and_configure_yum-cron
=========

Install and configure yum-cron

Requirements
------------

None.

Role Variables
--------------

- `automatic_reboots_after_kernel_updates`: If the user desires, she can set this variable to `true` and this role will create a script, that reboots after kernel updates. By default, this is disabled.

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
        - role: 'johanneskastl.install_and_configure_yum-cron'

License
-------

BSD-3-Clause

Author Information
------------------

I am Johannes Kastl, reachable via kastl@b1-systems.de.
