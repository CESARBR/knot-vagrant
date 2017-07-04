#Before installing this box, make sure that you have installed the [Vagrant](https://www.vagrantu.com "Vagrant") and [Vitual Box](https://www.virtualbox.org/ "VirtualBox") on you machine.

##Installing
* git clone git@github.com:CESARBR/knot-vagrant.git
* cd knot-vagrant 
* vagrant up

*To access vm just run the command:*

'''
vagrant ssh default

cd /knot/ 
'''
The "/knot/" folder is a mirror inside vm's "/src/" folder on your host.

###PS.: If it is to develop in S.O. Windows, see this [link](https://www.sitepoint.com/getting-started-vagrant-windows/) with installation and execution instructions