Vagrant.configure("2") do |config|
  config.vm.box = "boxen/debian-13"

  config.vm.provider "virtualbox" do |vb|
    vb.cpus = 2
    vb.memory = 2048
  end

  config.vm.network "forwarded_port", guest: 80, host: 8080
end
