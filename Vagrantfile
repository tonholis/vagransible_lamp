VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
	config.vm.box = "ubuntu/wily64"
	config.vm.network "forwarded_port", guest: 80, host: 8080
	config.vm.network "private_network", ip: "192.168.33.11"
	#config.vm.synced_folder "./", "/var/www"

	config.vm.provision :ansible do |ansible|
		ansible.playbook = "playbook.yml"
	end
end
