Vagrant Experiment
==================

This projects aim is to get familiar with
[Vagrant](http://vagrantup.com/ "Homepage for Vagrant").
Vagrant is described on its website as:

*Vagrant is a tool for building and distributing virtualized development environments.*

Environment
-----------

The prerequisites for this project are listed below. The are the same as per the
[walkthrough](http://vagrantup.com/docs/getting-started/index.html "Walkthrough on vagrant homepage").

* [VirtualBox](https://www.virtualbox.org/ "Homepage of VirtualBox") installed.
* [Ruby](http://www.ruby-lang.org/en/ "Homepage of Ruby") and [Rubygems](http://rubygems.org/ "Homepage for RubyGems.") installed.
* Vagrant installed

In addition to this is is advisable to use Ruby Version Manager
([rvm](http://beginrescueend.com/ "Homepage for Ruby Version Manager")). rvm allows you to transparantly
change ruby versions and gems between projects.

I personally set my environment up in the following manner.

    > rvm install 1.9.2
    > rvm use 1.9.2
    > rvm gemset create vagrant

Everytime I work on this project I execute the command below.

    > rvm use 1.9.2@vagrant

