ansible-zookeeper
=================

ZooKeeper playbook for Ansible

## Testing

    vagrant up ubuntu && vagrant ssh ubuntu
    cd /home/vagrant/roles/ansible-zookeeper
    bin/test

## Example Usage

    ---
    - hosts: zookeepers
    sudo: true

    roles:
    - {
        role: ansible-zookeeper,
        version: 3.4.6,
        myid: 1
      }

See this sample [playbook](https://github.com/AnsibleShipyard/ansible-galaxy-roles/blob/master/playbook.yml)
which shows how to use this playbook as well as others. It is part of [ansible-galaxy-roles](https://github.com/AnsibleShipyard/ansible-galaxy-roles) and
serves as a curation (and thus an example) of all our ansible playbooks.

## Our Other Mesos related playbooks

1. [ansible-mesos](https://github.com/AnsibleShipyard/ansible-mesos)
1. [ansible-marathon](https://github.com/AnsibleShipyard/ansible-marathon)
1. [ansible-chronos](https://github.com/AnsibleShipyard/ansible-chronos)
1. [ansible-mesos-docker](https://github.com/AnsibleShipyard/ansible-mesos-docker)
1. [ansible-zookeeper](https://github.com/AnsibleShipyard/ansible-zookeeper)