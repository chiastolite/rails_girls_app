# -*- mode: ruby -*-
# vi: set ft=ruby :

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box = "rails_tutorial"
  config.vm.box_url = "https://dl.dropboxusercontent.com/s/m9oqqxpkx3clqlw/val_rails_tutorial.box"

  # forward to rails server
  config.vm.network :forwarded_port, guest: 3000, host: 13000
end
