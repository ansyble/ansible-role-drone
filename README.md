[ ![Image](https://cloud.githubusercontent.com/assets/5514990/24834935/e0d1db04-1d1c-11e7-8ad0-53fd45ff13c3.png "Ansible") ](https://www.ansible.com/ "Ansible")

[![Build Status](https://travis-ci.org/ansyble/role-drone.svg?branch=master)](https://travis-ci.org/ansyble/role-drone)
[![Ansible Role](https://img.shields.io/ansible/role/16920.svg)](https://galaxy.ansible.com/ansyble/drone/)

[Ansible](http://www.ansible.com) role to deploy [drone.io](http://readme.drone.io)

### Install

```sh
ansible-galaxy install ansyble.drone
```

### Usage

```yml
drone_host: https://domake.io
drone_secret: 'my-secret'
drone_github_client_id: 'my-client-id'
drone_github_client_secret: 'my-client-secret'
```

### Defaults

```yml
drone_version: 0.6
drone_host: http://localhost
drone_ip_addr: 0.0.0.0
drone_port: 80
```
