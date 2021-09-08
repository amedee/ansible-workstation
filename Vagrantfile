Vagrant.configure("2") do |config|

  config.vm.box = "ubuntu/focal64"

  config.vm.provision "ansible_local" do |ansible|
    ansible.playbook = "local.yml"
  end

end
