# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
 config.vm.define :servidor do |servidor|
 servidor.vm.box = "ubuntu/jammy64"
 servidor.vm.network :private_network, ip: "192.168.50.3"
 servidor.vm.hostname = "servidor"
 servidor.vm.network :public_network
 end
 config.vm.define :cliente do |cliente|
 cliente.vm.box = "ubuntu/jammy64"
 cliente.vm.network :private_network, ip: "192.168.50.2"
 cliente.vm.hostname = "cliente"
 end

end
