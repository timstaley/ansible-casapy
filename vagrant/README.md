# Vagrant prerequisites
NB, you either need to install the vagrant-triggers plugin:

    vagrant plugin install vagrant-triggers
    
Or, comment out the `config.trigger` section of *Vagrantfile* and manually run

    ansible-galaxy install -p .vagrant/ansible_roles timstaley.base

from this folder, before you can carry on with 

    vagrant up
    
as usual.