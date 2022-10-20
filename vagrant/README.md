# vagrant-ubuntu-m1

Here is the vagrant file which is:
* installing docker 
* installing nginx
* making ssh access by key only
* adding users without sudo; with docker group (list of users is in userlist)

## Getting started
1. Install Vagrant on your machine [https://learn.hashicorp.com/collections/vagrant/getting-started](https://learn.hashicorp.com/collections/vagrant/getting-started).
2. Install a provider (e.g. VMware fusion). See [https://www.vagrantup.com/docs/providers/vmware](https://www.vagrantup.com/docs/providers/vmware). Make sure the vmware utility is up and running : ```sudo launchctl load -w /Library/LaunchDaemons/com.vagrant.vagrant-vmware-utility.plist```
3. Run ```vagrant init```, ```vagrant up``` being in the directory with the Vagrantfile.
4. To stop run ```vagrant halt```. To restore the state use ```vagrant destroy```.
5. To remove the box use ```vagrant box remove <box-name>```. Also, see [https://www.vagrantup.com/docs/cli/box#box-remove](https://www.vagrantup.com/docs/cli/box#box-remove).