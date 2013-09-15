# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "precise64"
  config.vm.hostname = "hydrogen"
  config.vm.box_url = "http://goo.gl/8kWkm"
  config.vm.network :forwarded_port, guest: 80, host:7000
end
