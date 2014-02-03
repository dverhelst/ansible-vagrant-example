Vagrant ansible integration
===========================

Required tools to make sure vagrant and ansible run OK:

  * Vagrant >= 1.4.3
  * Ansible >= 1.4
  * Virtualbox

Install Vagrant
===============

Download and install vagrant from [vagrantup.com](http://www.vagrantup.com/downloads.html)

Install Ansible
===============

The quickest way to get up and running with ansible is installing it in a virtualenv.

    virtualenv vagrant-ansible
    source vagrant-ansible/bin/activate
    pip install ansible

Running the project
===================

    vagrant up



This will provide you with 2 virtualmachines, one with httpd installed and running on it, and one without.

Note: You might want to run it twice, 'complex' infra is a bit tricky in Vagrant. When running this twice, both machines will be up and you will be able to use them both in your playbooks.


Author
======

Dieter Verhelst -- info@werus.be
