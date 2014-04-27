
Vagrant.configure('2') do |config|
  config.vm.box = 'Wheezy 64'
  config.vm.box_url = 'https://sovereign.lukecyca.com/vagrant/wheezy64.box'
  config.vm.hostname = 'pcloud.local'
  config.vm.network 'private_network', ip: '10.0.0.10'

  config.vm.provision :ansible do |ansible|
    ansible.playbook = 'playbook.yml'
    ansible.extra_vars = { ansible_ssh_user: 'vagrant', vagrant: true }

    # ansible.tags = ['common']
    # ansible.skip_tags = ['common']
    # ansible.verbose = 'vvvv'
  end
end

