# Learning note while doing the Udemy
It's recommended to know basic Linux commands before learn how to setup your VPS server. ``bash`` and ``cron`` skills are needed to automate Wordpress backups.

## Basic Setup
+ First time login, create non-root user and disable root login
+ Login as non-root user and set up ssh key pair login
+ Most importantly, set up your firewall, complex, pre-written rules are recommended
+ Set up and configure ``fail2ban`` which prevent brute break ins

## Install software for Wordpress
+ ``Apache`` install, configure harden and optimisation
+ ``MYSQL`` install, configure harden and optimisation
+ ``PHP`` install, configure harden and optimisation
+ ``Apache virtual hosts`` learn to configure multiple Wordpress sites

## Basic Server administration
+ Install ``mailutils`` and ``sendmail`` (required by Wordpress)
+ Keep VPS updated every time you login
+ Learn to read log files (both ``apache`` and ``fail2ban``)
+ Learn resource monitor with ``htop``

## Nice to have skills
+ Setup ``Nginx`` powered Wordpress sites
+ Setup ``HTTPS certificate`` for your Wordpress site
+ Install ``Redis Cache`` to speed up your Wordpress

## Wordpress
+ Wordpress command line tool
+ Databases and site files backups
+ ``Bash`` script and ``cron`` tasks
