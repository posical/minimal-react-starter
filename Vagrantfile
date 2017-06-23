# -*- mode: ruby -*-
# vi: set ft=ruby :

# This vagrant configuration can be used for testing this starter project on Ubuntu.
# https://docs.vagrantup.com.
Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu/trusty64"

  # As of June 23rd, 2017, this will install Node v6.11.0 and npm v3.10.10
  # npm install - succeeds
  # node server.js - succeeds
  # curl http://localhost:3000 - succeeds
#   config.vm.provision "shell", inline: <<-SHELL
# curl -sL https://deb.nodesource.com/setup_6.x | sudo -E bash -
# apt-get -y install nodejs
# SHELL

  # As of June 23rd, 2017, this will install Node v8.1.2 and npm v5.0.3
  # npm install - succeeds
  # node server.js - succeeds
  # curl http://localhost:3000 - succeeds
  config.vm.provision "shell", inline: <<-SHELL
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
apt-get -y install nodejs
SHELL


end
