# vagrantlampmulti
1. Vagrant up
2.Let vagrant start you 3 virtual machines "control","app1","db1"
3.vagrant ssh controll
4. cd ..
5. vim etc/ansible/hosts
6. Copy and paste hosts.ini which is located in ansible folder in the project (./ansible/hosts.ini) Could not find a fix for ansible ping


password for all VM's: vagrant

Acess apache:
vagrant ssh app1
curl 192.168.135.111 to see apache working
Acess mysql:
vagrant ssh db1
mysql -u deploy -p
password: vagrant
