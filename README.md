# Cerobox

Vagrant Box for local LEMP development for Windows and Linux

## Content

1. [Software Included](#software-included)
2. [Software needed](#software-needed)
3. [Usage](#usage)
4. [Where to put the code](#where-to-put-the-code)
5. [Visualize your development](#visualize-your-development)
6. [Credentials](#credentials)
7. Help Tutorials
	* [Ubuntu 17.04 Zesty](#ubuntu-1704-zesty)
	* [Windows](#windows)

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
* [Cmder(Windows)](http://cmder.net/)

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

## Where to put the code

Your operating system along with Cerobox shares a synchronized folder called "public" where the source code of your application will be.

So you can edit the source code from your operating system and run with the Cerobox web server.

![alt text](http://box.cerocodes.com/images/put_code.jpg "Where to put the code?")

## Visualize your development

Just enter the following IP in your browser: http://192.168.33.10

![alt text](http://box.cerocodes.com/images/ip.jpg "Vagrant up")

## Credentials
### SSH
| Feature      | Value         |
| ------------ | ------------- |
| Host         | 192.168.33.10 |
| User         | vagrant       |
| Password     | vagrant       |

### Mysql
| Feature      | Value         |
| ------------ | ------------- |
| Host         | 192.168.33.10 |
| User         | root          |
| Password     | root          |
| Database     | cerobox       |

# Help Tutorials
## Ubuntu 17.04 Zesty
* Installing Git on Ubuntu 17.04 Zesty
* Install Virtualbox on ntu 17.04 Zesty
* Installing Vagrant on Ubuntu 17.04 Zesty
* 192.168.33.10 Not working Ubuntu

## Windows
* Installing Git on Windows
* Installing Cmder onindows
* Installing VirtualBox on Windows
* Installing Vagrant on Windows




