Vagrant Centos 6 Box
====================

*Ruby 1.9.2
*RVM
*Chef 
*VirtualBox Guest Additions
*Development Tools

This box is setup for vagrant, to install simple run the following:

    $ gem install vagrant
    $ vagrant box add centos-6 https://vagrant-centos-6.s3.amazonaws.com/centos-6.box
    $ vagrant init centos-6
    $ vagrant up