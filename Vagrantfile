# -*- mode: ruby -*-
# vi: set ft=ruby :
VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
    config.vm.box = "precise32"
    config.vm.network :private_network, ip: "10.0.0.100"
    # nginx/apache
    config.vm.network :forwarded_port, guest: 80, host: 8080

    # Folder sync
    # config.vm.synced_folder ".", "/Projects", id: "vagrant-root"
end
