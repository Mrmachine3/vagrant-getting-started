# Getting started with Vagrant 

## Intalling Vagrant on Ubuntu 18.04
- Upgrade host package repositories and install virtualbox as the vagrant provider on the target host

```bash
sudo apt update
sudo apt install virtualbox
```

- Download vagrant directly from Hashicorp to ensure compatibility with target host

```bash
curl -O https://releases.hashicorp.com/vagrant/2.2.6/vagrant_2.2.6_x86_64.deb
sudo apt install ./vagrant_2.2.6_x86_64.deb
```

- Verify proper installation of vagrant on target host

`vagrant --version`

- Initialize vagrant box ```vagrant up```

- Login to vagrant box ```vagrant ssh```

- Stop vagrant box ```vagrant halt```

- Destroy vagrant box instance 	```vagrant destroy```


