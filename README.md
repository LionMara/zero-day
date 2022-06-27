## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)

## General info
This project brings into life the vagrant vm.
This enables you to start ubuntu in your vm.

## Tehnologies
Project is created using the following:
* VirtualBox
* Vagrant
* Ubuntu focal64

## Setup
To run a vm in your machine the following steps are
followed:

```
$ vagrant box add ubuntu/focal64
$ vagrant init ubuntu/focal64
$ vagrant plugin install vagrant-vbguest
$ vagrant up
$ vagrant ssh
```