# VirtualBox for Ruby on Rails App Developmet

以下のサイトを参考に作成したアプリ開発のテンプレートです。

* https://gorails.com/guides/using-vagrant-for-rails-development

## Requirements

* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)


## How To Build The Virtual Machine

Vagrant:

    host $ vagrant plugin install vagrant-vbguest
    host $ vagrant plugin install vagrant-librarian-chef
    host $ vagrant plugin install vagrant-vbox-snapshot

Building the virtual machine:

    host $ git clone https://github.com/katsuhiko/template-rails.git
    host $ cd template-rails
    host $ vagrant up

## How To New Rails Project

* https://github.com/RailsApps/rails-composer

## How To New Rails Plugin

* https://gist.github.com/tomoyukiinoue/7968556
* http://www.andrewhavens.com/posts/27/how-to-create-a-new-rails-engine-which-uses-rspec-and-factorygirl-for-testing/

