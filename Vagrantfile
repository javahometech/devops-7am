Vagrant.configure("2") do |config|
  config.vm.define "server1" do |server1|
    server1.vm.box = "bento/centos-6.7"
    server1.vm.network "private_network", ip: "192.168.50.10"
  end

  config.vm.define "server2" do |server2|
    server2.vm.box = "bento/centos-6.7"
    server2.vm.network "private_network", ip: "192.168.50.11"
  end
end
