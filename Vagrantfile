# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|

  config.vm.box = "cerocodes/box"
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.hostname = "Cerobox"
  config.vm.synced_folder ".", "/var/www", :mount_options => ["dmode=777", "fmode=666"]

  config.vm.provider "virtualbox" do |vb|
     vb.customize [ "modifyvm", :id, "--uartmode1", "file", File.join(Dir.pwd, "cerobox.log") ]
  end

end
