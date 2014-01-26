# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = 'ubuntu'
  
  config.vm.define "puppet" do |puppet|
    puppet.vm.hostname = "puppet"
  end

  config.vm.define "control" do |control|
    control.vm.hostname = "control"
  end

  config.vm.define "neutron" do |neutron|
    neutron.vm.hostname = "neutron"
  end

  config.vm.define "compute1" do |compute1|
    compute1.vm.hostname = "compute1"
  end

end
