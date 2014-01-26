# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = 'ubuntu'
  
  config.vm.define "puppet" do |puppet|
    puppet.vm.hostname = "puppet"
    puppet.vm.network "private_network", ip: "10.10.0.10", netmask: "255.255.0.0"
  end

  config.vm.define "control" do |control|
    control.vm.hostname = "control"
    control.vm.network "private_network", ip: "10.10.1.2", netmask: "255.255.0.0"
  end

  config.vm.define "neutron" do |neutron|
    neutron.vm.hostname = "neutron"
    neutron.vm.network "private_network", ip: "10.10.1.3", netmask: "255.255.0.0"
  end

  config.vm.define "compute1" do |compute1|
    compute1.vm.hostname = "compute1"
    compute1.vm.network "private_network", ip: "10.10.1.4", netmask: "255.255.0.0"
  end

end
