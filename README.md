## Overview

VIP Quickstart is a local development environment for WordPress.com VIP developers. It provides developers with an environment that closely mirrors WordPress.com along with all the tools we recommend developers use. VIP Quickstart should not be used to run a production site.

## Requirements

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](http://www.vagrantup.com/downloads.html)

## Setup

* Set `10.86.73.80 qz.dev` in `/etc/hosts`
* `git clone --recursive https://github.com/Quartz/vip-quickstart.git`
* `cd vip-quickstart`
* `vagrant up`
* `cd www/wp-content/themes/vip/qz-api`
* `git clone https://github.com/Quartz/qz-api.git`
* `vagrant ssh`
* `wp theme activate vip/qz-api`
* `wp qz_quickstart_helper setup`

## What You Get

*   Ubuntu 12.04
*   WordPress trunk
*   WordPress.com VIP Shared Plugins repository
*   WordPress multisite
*   WordPress unit tests
*   Custom WordPress.com modifications
*   WP-CLI
*   MySQL
*   PHP
*   Nginx
*   PHPUnit

## Acknowledgements

Thanks to the following projects that VIP Quickstart is built on:

* [Vagrant](http://vagrantup.com/)
* [Puppet](http://puppetlabs.com/)
* [Varying Vagrant Vagrants](https://github.com/10up/varying-vagrant-vagrants)
* [WP-CLI](http://wp-cli.org)
* [puppet-mysql](https://github.com/example42/puppet-mysql)
* [puppet-nginx](https://github.com/example42/puppet-nginx)
* [puppet-php](https://github.com/jippi/puppet-php)
* [puppi](https://github.com/example42/puppi)
* [puppet-wp](https://github.com/rmccue/puppet-wp)

If you're not developing for WordPress.com VIP, you might want to check out these other Vagrant/WordPress projects

* [VVV](https://github.com/Varying-Vagrant-Vagrants/VVV)
* [Salty WordPress](https://github.com/humanmade/Salty-WordPress)
* [Vagrant Genesis](https://github.com/genesis/wordpress/)
* [VagrantPress](https://github.com/chad-thompson/vagrantpress)
