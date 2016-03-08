Common
======

Some common tasks for Debian hosts

Requirements
------------

Ansible 1.9 or higher. Platform requirements are listed in the metadata file.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: SphericalElephant.common
           common_basic_packages: ['vim', 'zsh'],
           common_mailer: False,
           common_resolvconf_nameservers: ['1.2.3.4', '2.3.4.5']

License
-------

This project is released under the MIT license (see the LICENSE file).
