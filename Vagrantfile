Vagrant.configure(2) do |config|
  config.vm.box = "nton-edu/shirawagi-webmail"
  config.vm.network "forwarded_port", guest: 3000, host: 3000
  config.vm.network "private_network", ip: "192.168.33.10"
end