# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|

  config.vm.define "minty17" do |config|
    config.vm.box = "npalm/mint17-amd64-cinnamon"
    config.vm.hostname = "minty17"
    config.vm.network "private_network", ip: "192.168.99.99"
    config.vm.provider "virtualbox" do |vb|
      vb.memory = 2048
      vb.cpus = 2
    end  
  end

end
