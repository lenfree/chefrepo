# -*- mode: ruby -*-
# vi: set ft=ruby :

# Vagrantfile API/syntax version. Don't touch unless you know what you're doing!
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|

  config.vm.define "node1" do |node|
    node.vm.box = "centos6.5"
  end

  config.vm.define "node2" do |node|
    node.vm.box = "centos6.5"
  end

  config.vm.network :public_network,  auto_config: true

end
