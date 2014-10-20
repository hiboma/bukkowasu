# -*- mode: ruby -*-

VAGRANTFILE_API_VERSION = "2"

Vagrant.configure(VAGRANTFILE_API_VERSION) do |config|
  config.vm.box     = "CentOS 6.5 x86_64"
  config.vm.box_url = "https://github.com/2creatives/vagrant-centos/releases/download/v6.5.1/centos65-x86_64-20131205.box"
  config.vm.provider :virtualbox do |vb|
    vb.gui = true
  end

  # Prevent Vagrantfile to be deleted by `rm -rfv /` !!!!
  config.vm.synced_folder ".", "/vagrant", disabled: true
end
