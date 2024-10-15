Vagrant Base

Project that contain directory that you can include in your projects if you want a local virtual server.
It will create a custom vagrant box file with Packer tool.

Virtual Server based on Ubuntu 18 OS (modify in your convenience)

This vagrant box includes :
- Apache 2.4
- PHP 7.3 (with XDebug)
- MariaDB 10

with those linux tools : 

- install nano
- install vim
- install aptitude
- install git
- install dos2unix
- install net-tools
- install nmap
                  

How to :

1. copy/paste vagrant directory to your project root path
2. download your Ubuntu 18 iso (server version!) and copy in the vagrant/files directory
3. change the "iso_url" parameter of the packer template file
4. confirm the "config.vm.box_url" in the Vagrantfile
5. launch packer


Requirements :

- VirtualBox engine [VirtualBox engine](https://www.virtualbox.org/)
- Vagrant system [Vagrant system](https://www.vagrantup.com/)
- Packer tool [Packer tool](https://developer.hashicorp.com/packer)
