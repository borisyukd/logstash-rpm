# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "CentOS-6.4-minimal"
  config.vm.provision :shell, :path => "vagrant/setup.sh"
end
