# vagrant-ansible-template

A template for [Vagrant](http://www.vagrantup.com) which automatically configures ansible to be used on the virtual machines.

## Usage
```
git clone https://github.com/jeremymturner/vagrant-ansible-template.git
cd vagrant-ansible-template
vagrant up
ansible -m ping all
```

### Notes
* Requires the latest [Vagrant](http://www.vagrantup.com)
* Requires the latest [VirtualBox](https://www.virtualbox.org)
* Requires the latest [Ansible](http://www.ansible.com)
