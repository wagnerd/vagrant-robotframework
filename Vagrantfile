# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  #desktop
  config.vm.box = "peru/ubuntu-18.04-desktop-amd64"
  config.vm.box_version = "20180503.01"

  config.vm.network "forwarded_port", guest: 8080, host: 8080
  config.vm.network "forwarded_port", guest: 8081, host: 8081

  config.vm.provider "virtualbox" do |vb|
    vb.name = "UbuntuDesktop1804_robotframework"
    vb.memory = "4096"
    vb.cpus = 4
  end
  
  config.vm.synced_folder ".", "/vagrantsync"

  config.vm.provision "shell" do |s|
    s.path = "provision.sh"
  end
end
