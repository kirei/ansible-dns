Vagrant.configure("2") do |config|
  config.vm.box = "generic/centos8"
  config.vm.provision "ansible" do |ansible|
      ansible.verbose = "v"
      ansible.playbook = "playbook.yml"
    end
end
