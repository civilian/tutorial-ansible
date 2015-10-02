# -*- mode: ruby -*-
# vi: set ft=ruby :

# TODO: Add variables to beeing able to configure the host.

# All Vagrant configuration is done below. # Please don't change it unless you know what
# you're doing.
Vagrant.configure(2) do |config|
    config.vm.box = "debian/jessie64"

    # We run the ansible here too for testing
    config.vm.provision "ansible" do |ansible|
        ansible.playbook = "ansible.yaml"
    end
end
