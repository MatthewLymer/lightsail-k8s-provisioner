# -*- mode: ruby -*-
# vi: set ft=ruby :

Vagrant.configure("2") do |config|
  config.vm.box = "generic/debian10"

  config.vm.provision "ansible" do |ansible|
    ansible.playbook = "deployment/playbook.yml"
  end
end
