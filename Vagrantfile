Vagrant.configure("2") do |config|
	# server config
	config.vm.define :server do |server_config|
		server_config.vm.box = "bento/ubuntu-14.04"
		server_config.vm.network "forwarded_port", guest: 8080, host: 8080
	  end
end
