## docker-cluster-install

Ansible playbook to install docker swarm cluster (with registry)

## How

### Customize parameters
Customize parameters in file .config.yml
```sh
cd docker-cluster-install
cp vars/config.yml .config.yml
vi .config.yml
```

### Run with vagrant:
```sh
vagrant up
```
or
```sh
vagrant provision
```

### Run with inventory file
```sh
cp hosts .hosts
vi .hosts
ansible-playbook -i .hosts install-machine.yml
```
