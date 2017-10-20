# -*- mode: ruby -*-
# vi: set ft=ruby :

# All Vagrant configuration is done below. The "2" in Vagrant.configure
# configures the configuration version (we support older styles for
# backwards compatibility). Please don't change it unless you know what
# you're doing.
Vagrant.configure("2") do |config|

    config.vm.define "nodejs" do |node|
        node.vm.box = "ubuntu/xenial64"
        node.vm.hostname = "nodejs"
        node.vm.network "public_network", ip: "192.168.1.50"
        node.vm.provision :shell, path: "node-6-11-4.sh"
    end

end
