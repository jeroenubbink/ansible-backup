Vagrant.configure("2") do |config|
  config.vm.guest = :freebsd
  config.vm.synced_folder ".", "/vagrant", id: "vagrant-root", disabled: true
  config.ssh.shell = "sh"
  config.vm.base_mac = "080027D14C66"

  config.vm.provider :libvirt do |libvirt|
    libvirt.cpus = 2
    libvirt.storage :file, :size => '20G'
  end
end
