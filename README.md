control-kickstart
=========

Installs dependencies for a CentOS Ansible control system. Install like...
`ansible-galaxy install --roles-path=/Users/andrew/ansible-roles/ amaurer.control-kickstart`


Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.


Dependencies
------------

None


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: amaurer.control-kickstart }

Test
-------
`cd tests`
`ansible-playbook test.yml --check`


License
-------

Apache 2.0


Author Information
------------------

http://www.maurer.me/
