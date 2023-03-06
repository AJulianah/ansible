# Configuration de la machine Debian
Vagrant.configure("2") do |config|
    config.vm.define "debian" do |debian|
      debian.vm.box = "debian/buster64"
      debian.vm.hostname = "debian"
      debian.vm.network "private_network", ip: "192.168.33.30"
      debian.vm.provider "virtualbox" do |vb|
        vb.memory = "1024"
        vb.cpus = "1"
      end
    end
end