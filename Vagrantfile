Vagrant.configure("2") do |config|
  config.vm.box = "vatman/xenial64"
  config.vm.provision :shell, :path => "hello.sh", :privileged => false
end
