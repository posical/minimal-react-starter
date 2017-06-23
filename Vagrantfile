# -*- mode: ruby -*-
# vi: set ft=ruby :

# This vagrant configuration can be used for testing this starter project on Ubuntu.
# https://docs.vagrantup.com.
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  config.vm.provision "shell", inline: <<-SHELL
curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
apt-get -y install nodejs
SHELL

end
