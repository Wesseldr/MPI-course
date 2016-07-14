# Supporting files for the Manageable Puppet Infrastructure course on Udemy

# Intro
Presentation intro: https://my.visme.co/projects/dmv33067-puppet-mpi-course

Sign up through this link for a 20% discount on the course: https://www.udemy.com/manageable-puppet-infrastructure/?couponCode=GITHUB20

## Prerequisites
* Intermediate Puppet knowledge
* 2 VMs with internet connection
  * Puppet Master
    * 4G memory, 8G if Puppet Enterprise
    * at least 2 cores, preferably 4.
  * Git server

# Links
## Getting started
CentOS 7 image download: https://s3-eu-west-1.amazonaws.com/virtualboxes.org/CentOS7-base.ova.torrent

# Choices
* [Puppet Enterprise](https://puppet.com)
* [Satellite server](https://access.redhat.com/products/red-hat-satellite)
* [Foreman](http://theforeman.org)
* [Katello](http://www.katello.org/)
* [Lean and mean](https://docs.puppet.com/guides/puppetlabs_package_repositories.html#yum-based-systems) with some dashboard

# Installing Lean and Mean
* [Puppet yum repositories](https://docs.puppet.com/guides/puppetlabs_package_repositories.html#yum-based-systems)

# Initial modules
* https://forge.puppet.com/camptocamp/puppetserver
* https://forge.puppet.com/puppetlabs/puppetdb

## Install GitLab
https://about.gitlab.com/downloads/#centos7

## Other pages
* [R10k](R10k.md)
* [Git-flow](git-flow.md)
* [Why code review?](why-code-review.md)
* [Workflows](workflows.md)
* [Node classification](classification.md)
* [Webconsole notes](webconsole.md)
