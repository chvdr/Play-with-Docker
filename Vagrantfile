# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

config.vm.define "webone" do |webone|
webone.vm.box="centos/7"
webone.vm.hostname = "hostone"
# Change with your own IP-Address:
webone.vm.network "public_network", ip: "192.168.88.100"
webone.vm.provision "shell", path: "provision.sh"
end
end
