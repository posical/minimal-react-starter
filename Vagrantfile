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
#   config.vm.provision "shell", inline: <<-SHELL
# curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
# apt-get -y install nodejs
# SHELL


  # This will install Node v4.8.3 and npm v2.15.11
  # https://stackoverflow.com/questions/16898001/installing-a-specific-node-version-in-ubuntu
  # The download link below is from:
  # https://deb.nodesource.com/node_4.x/pool/main/n/nodejs/
  config.vm.provision "shell", inline: <<-SHELL
curl -s -O https://deb.nodesource.com/node_4.x/pool/main/n/nodejs/nodejs_4.8.3-1nodesource1~trusty1_amd64.deb
apt-get install rlwrap -y
dpkg -i nodejs_4.8.3-1nodesource1~trusty1_amd64.deb
SHELL

end
