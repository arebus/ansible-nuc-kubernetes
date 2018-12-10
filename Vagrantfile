# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  config.vm.network "private_network", name: "vboxnet1", ip: "172.28.128.10"
  config.vm.hostname = "kubemaster.example.com"

  config.vm.provider "virtualbox" do |v|
	  v.name = "kubemaster"
	  v.memory = 2048
	  v.cpus = 2
  end

end
