# -*-ruby-*-
Vagrant.configure("2") do |config|
  config.vm.box = "centos/7"
  # config.vm.box = "bento/centos-8.5"
  # config.vm.box_version = "202112.19.0"
  config.vm.hostname = "test-ansible-box"
  config.disksize.size = "64GB"
  # config.vm.network "private_network", ip: "10.10.10.10"
  config.vm.provider "virtualbox" do |v|
    v.memory = 4096
    v.cpus = 2
    # Display the VirtualBox GUI when booting the machine
    # v.gui = true
  end
end
