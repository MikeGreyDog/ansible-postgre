Vagrant.configure("2") do |config|


    config.vm.define "node00" do |node00|
        node00.vm.box = "centos/7"
        node00.vm.hostname = 'node00'
        node00.vm.network :private_network, ip: "192.168.33.100"
        node00.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    config.vm.define "node01" do |node01|
        node01.vm.box = "centos/7"
        node01.vm.hostname = 'node01'
        node01.vm.network :private_network, ip: "192.168.33.101"
        node01.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    config.vm.define "node10" do |node10|
        node10.vm.box = "centos/7"
        node10.vm.hostname = 'node10'
        node10.vm.network :private_network, ip: "192.168.33.110"
        node10.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

    config.vm.define "node11" do |node11|
        node11.vm.box = "centos/7"
        node11.vm.hostname = 'node11'
        node11.vm.network :private_network, ip: "192.168.33.111"
        node11.vm.provider "virtualbox" do |vb|
                vb.memory = "1024"
                vb.cpus = "1"
        end
    end

end
