Role Name
=========

Installing "The ultimate vim configuration"

Requirements
------------

No Requirements

Role Variables
--------------

state:
  - 'install'
  - 'uninstall'
  - 'full_uninstall' # NOT recomended cause may delete important stuff
  - 'update'

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: example
      roles:
         - ansible.role.vim
      vars:
        path: "/opt"
        users: "--all"
        state: 'install'

License
-------

MIT

Author Information
------------------

AloySobek
