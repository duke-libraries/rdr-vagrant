# rdr-vagrant
Vagrant VM for running RDR (Research Data Repository). This is a modified version of the [samvera-vagrant](https://github.com/samvera-labs/samvera-vagrant) VM.

## Requirements

* [Vagrant](https://www.vagrantup.com/) version 1.8.5+
* [VirtualBox](https://www.virtualbox.org/)

## Setup

1. `git clone https://github.com/duke-libraries/rdr-vagrant.git`
2. `cd rdr-vagrant`
3. `vagrant up`

You can shell into the machine with `vagrant ssh` or `ssh -p 2222 vagrant@localhost`

## Submodule

Includes [DUL RDR](https://github.com/duke-libraries/rdr) as a submodule
