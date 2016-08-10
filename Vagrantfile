Vagrant.configure(2) do |config|

  config.vm.box = 'bento/ubuntu-16.04'

  config.vm.define "xenial" do |server|
    server.vm.network "private_network", ip: "10.0.0.100"
  end
end
