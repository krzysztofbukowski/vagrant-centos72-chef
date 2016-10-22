# -*- mode: ruby -*-
# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure(2) do |config|
    config.vm.box = "boxcutter/centos72"
    config.vm.box_check_update = false

    config.vm.provider :virtualbox do |vb|
        vb.name = "centos72-chef"
    end

$script = <<SCRIPT
    rpm -ivh https://packages.chef.io/stable/el/7/chef-12.15.19-1.el7.x86_64.rpm
SCRIPT

    config.vm.provision "shell", inline: $script
end
