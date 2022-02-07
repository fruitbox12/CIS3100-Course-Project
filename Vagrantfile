Vagrant.configure("2") do |config|

  # Use :ansible or :ansible_local to
  # select the provisioner of your choice
  config.vm.provision :ansible do |ansible|
    ansible.playbook = "main.yml"
  end
end
