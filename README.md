# Cerobox

Vagrant Box for local LEMP development for Windows and Linux

## Software Included
* Ubuntu Ubuntu 16.04.2 LTS
* Nginx v1.11.9
* PHP v7.1.5
* Mysql v5.7.18
* Composer v1.4.2
* git v2.7.4

## Software needed
* [Virtualbox](https://www.virtualbox.org/)
* [Vagrant](https://www.vagrantup.com/)

## Usage
### 1.- Clone
`$ git clone https://github.com/cerocodes/box.git myProject`

![alt text](http://box.cerocodes.com/images/clone.jpg "Clone")

### 2.- Run
`$ cd myProject`
`$ vagrant up`

![alt text](http://box.cerocodes.com/images/vagrant_up.jpg "Vagrant up")

### 3.- SHH
`$ vagrant ssh`

![alt text](http://box.cerocodes.com/images/vagrant_ssh.jpg "Vagrant SHH")

## Where to put the code?

Your operating system along with Cerobox shares a synchronized folder called "public" where the source code of your application will be.

So you can edit the source code from your operating system and run with the Cerobox web server.

![alt text](http://box.cerocodes.com/images/put_code.jpg "Where to put the code?")

## Visualize your development

Just enter the following IP in your browser: http://192.168.33.10

![alt text](http://box.cerocodes.com/images/ip.jpg "Vagrant up")




