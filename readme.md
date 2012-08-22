# Zend Framework Skeleton (with Vagrant)
Vagrant box based setup that installs a virtual machine running CentOS
configured with 

* apache
* php
* mysql
      
and setup with /var/www/html mapped to a zend framework 2 application. 

## Using

- install [vagrant](http://www.vagrantup.com)
- clone this repo
- type vagrant up
- navigate to http://192.168.50.4 
- profit!

Optionally you may map the ip to a host name in your /etc/hosts file,
for example http://local.exmaple.com.