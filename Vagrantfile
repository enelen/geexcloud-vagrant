# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define "puppet" do |puppet|
    puppet.vm.box = "ubuntu"
  end

  config.vm.define "control" do |control|
    control.vm.box = "ubuntu"
  end

  config.vm.define "neutron" do |neutron|
    neutron.vm.box = "ubuntu"
  end

  config.vm.define "compute1" do |compute1|
    compute1.vm.box = "ubuntu"
  end

end
