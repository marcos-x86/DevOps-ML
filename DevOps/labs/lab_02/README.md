# Vagrantfile to manage OpenStack Cloud instance (Deployment Server)

This Vagrantfile can manage a OpenStack Cloud Instance using the OpenStack provider and Vagrant-env plugins. Also this vagrant file perform the installation of:
* Oracle JDK 8u151
* NodeJs 6.11
* MongoDB (Docker container)

### Requirements
* Vagrant
* Vagrant OpenStack Provider plugin
* Vagrant Docker-Compose plugin
* Vagrant-env plugin
* OpenStack Server

### Execution steps

1) Install all plugins described above
```
$ vagrant plugin install vagrant-openstack-provider
$ vagrant plugin install vagrant-docker-compose
$ vagrant plugin install vagrant-env
```
2) Download the Vagrantfile and .env files to a desired folder
3) Open and edit the .env file with your credentials
6) Run the following command in a terminal located in the desired folder
```
$ vagrant up
```
