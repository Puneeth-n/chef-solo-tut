# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.define "lb01" do |lb01|
    lb01.vm.box = "ubuntu/trusty64"
    lb01.vm.hostname = "chef-tut"
    lb01.vm.network :private_network, ip: "10.11.12.50"
  end
end
