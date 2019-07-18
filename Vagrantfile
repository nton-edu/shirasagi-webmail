Vagrant.configure("2") do |config|
  config.vm.box = "dduportal/alpine2docker"
  config.vm.network "forwarded_port", guest: 3000, host: 80
  config.vm.network "private_network", ip: "192.168.33.10"
  config.vm.synced_folder "./shared", "/home/vagrant/shared"
end