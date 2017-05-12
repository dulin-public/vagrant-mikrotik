# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.provider  "virtualbox"
  config.vm.box = "dulin/mikrotik"
  config.vm.box_version = "6.37.4"
  config.ssh.username = "vagrant"
  config.ssh.password = "vagrant"
  config.ssh.keys_only = false
  config.ssh.insert_key = false
  config.vm.box_check_update = false
  config.vm.synced_folder ".", "/vagrant", disabled: true
end
