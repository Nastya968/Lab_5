Vagrant.configure("2") do |config|

  config.vm.box = "centos/7"

  config.vm.provision "file", source: "file-mover.service", destination: "~/file-mover.service"

  config.vm.provision "shell", path: "hometask5.sh"
end