Rails sample
===

Requirement
---

* [VirtualBox](https://www.virtualbox.org/)
    * >= 4.3.6
* [Vagrant](http://www.vagrantup.com/)
    * >= 1.4.1

Usage
---

1. `git clone https://github.com/chiastolite/rails_girls_app.git`
2. `vagrant up`
3. `vagrant ssh`
4. `cd /vagrant` in virtual machine
5. `bundle; rake db:migrate; foreman start` in virtual machine
6. access http://localhost:13000/
