Vagrant.configure("2") do |config|
  
  # Create the first machine
  config.vm.define "machine1" do |machine1|
    machine1.vm.box = "ubuntu/focal64"
    machine1.vm.hostname = "machine1"
    machine1.vm.network "private_network", ip: "192.168.50.10"
  end

  # Create the second machine
  config.vm.define "machine2" do |machine2|
    machine2.vm.box = "ubuntu/focal64"
    machine2.vm.hostname = "machine2"
    machine2.vm.network "private_network", ip: "192.168.50.11"
  end

end
