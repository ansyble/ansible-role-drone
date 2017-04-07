[ ![Image](https://cloud.githubusercontent.com/assets/5514990/21614528/5c56d772-d20c-11e6-8670-577f2dd7ca9b.png "Ansible") ](https://www.ansible.com/ "Ansible")

[![Build Status](https://travis-ci.org/ansyble/role-drone.svg?branch=master)](https://travis-ci.org/ansyble/role-drone)
[![Ansible Role](https://img.shields.io/ansible/role/16912.svg)](https://galaxy.ansible.com/ansyble/drone/)

[Ansible](http://www.ansible.com) role to deploy [drone.io](http://readme.drone.io)

### Install

```sh
ansible-galaxy install ansyble.drone
```

### Usage

```yml
drone_secret: 'my-secret'
drone_github_client_id: 'my-client-id'
drone_github_client_secret: 'my-client-secret'
```

### Defaults

```yml
drone_version: 0.5
drone_ip_addr: 0.0.0.0
drone_port: 80
```
