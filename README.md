# timstaley.casapy

An [Ansible][] [role][] that provides an installation of 
the standard [CASA][] package, including the *casapy* command line environment.

[Ansible]: http://www.ansible.com/configuration-management
[role]: http://docs.ansible.com/ansible/playbooks_roles.html
[CASA]: http://casa.nrao.edu/

Dependencies
------------

This role makes use of [timstaley.base][] to ensure some basic tools 
(git,pip,virtualenv) are available.

[timstaley.base]: https://github.com/timstaley/ansible-base


License
-------

BSD