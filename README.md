# Vagransible
A recipe to create a LAMP server using Ansible and Vagrant 

* ubuntu/wily64
* Apache
* PHP 5.6.11
* MariaDB
* WKHTMLtoPDF (to generate PDF files based on HMTL)


#Pre-requisites (OSX)

Tested on OSX El Captain

##Vagrant
	
	https://www.vagrantup.com/downloads.html

##Ansible
	
	pip install ansible

##MySQL module
	
	pip install MySQL-python

#Run

	vagrant up

And check it out http://192.168.33.11/