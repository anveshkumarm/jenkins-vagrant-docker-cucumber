# author : anvesh
# description : base box for docker container deployment and cucumber test run

Vagrant.configure("2") do |config|
  config.vm.box = "ubuntu-14.04.box"
  config.vm.hostname = "DockerTestEnv"
  config.vm.network :private_network, ip: "192.168.10.20"
end