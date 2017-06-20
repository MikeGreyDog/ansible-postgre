Vagrant.configure("2") do |config|
    config.vm.synced_folder ".", "/vagrant", type: "virtualbox"	

    config.vm.define "node00" do |node00|
        node00.vm.box = "geerlingguy/centos7"
        node00.vm.hostname = 'node00'
        node00.vm.network :private_network, ip: "192.168.33.100"
        node00.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    config.vm.define "node01" do |node01|
        node01.vm.box = "geerlingguy/centos7"
        node01.vm.hostname = 'node01'
        node01.vm.network :private_network, ip: "192.168.33.101"
        node01.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    config.vm.define "pgpool00" do |pgpool00|
        pgpool00.vm.box = "geerlingguy/centos7"
        pgpool00.vm.hostname = 'pgpool00'
        pgpool00.vm.network :private_network, ip: "192.168.33.120"
        pgpool00.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    # config.vm.define "pgpool01s" do |pgpool01s|
    #     pgpool01s.vm.box = "centos/7"
    #     pgpool01s.vm.hostname = 'pgpool01s'
    #     pgpool01s.vm.network :private_network, ip: "192.168.33.121"
    #     pgpool01s.vm.provider "virtualbox" do |vb|
    #             vb.memory = "1024"
    #             vb.cpus = "1"
    #     end
    # end

end
