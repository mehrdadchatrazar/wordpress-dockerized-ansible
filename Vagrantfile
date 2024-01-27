Vagrant.configure("2") do |config|
  config.vm.box = "bento/ubuntu-22.04"
  config.vm.network "private_network", ip: "192.168.56.101"

  config.vm.provider "virtualbox" do |vb|  
    # Customize the amount of memory on the VM:
    vb.memory = "2048"
    vb.cpus = "4"
  end

  config.vm.provision "shell", inline: <<-SHELL
    apt-get update
  SHELL
end
