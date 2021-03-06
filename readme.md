#Vagrant-Chef
Vagrant Chef allows developers to test recipes locally on a VM consistently from a clean state.

###Prerequisites

* Download and install [Vagrant](http://www.vagrantup.com).
* Download and install [VirtualBox](http://www.virtualbox.org).
* Download repository `git clone git@github.com:giacomo81/vagrant-chef.git`

###Create VirtualBox VM using Vagrant
*(This repositories Vagrant files will only work if combined with the [Packer-Vagrant](https://github.com/giacomo81/packer-vagrant) project)*

####From the platform directory (i.e. `$ cd centos6.5`) execute the vagrant commands

      $ vagrant up

**SSH into vagrant box**

      $ vagrant ssh

**Reprovision**

      $ vagrant provision

**Destroy VM's**

      $ vagrant destroy
