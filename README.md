
williamyeh.docker-tools for Ansible Galaxy
============

Install common tools for Docker.


## Summary

Role name in Ansible Galaxy: **[williamyeh.docker-tools](https://galaxy.ansible.com/list#/roles/3230)**

This Ansible role has the following features:

 - Install official tools for Docker.
 - Install common 3rd-party tools for Docker.



## Role Variables

### Optional variables

User-installable configuration files (by Ansible's template system):

```
# install path; default = '/usr/local/bin'
docker_tools_path
```

## Usage


### Step 1: add role

Add role name `williamyeh.docker-tools` to your playbook file.


### Step 2: add variables

Set vars in your playbook file.

Simple example:

```yaml
---
# file: simple-playbook.yml

- hosts: all

  roles:
    - williamyeh.docker-tools

  vars:
    # customize install path, if necessary
    docker_tools_path: '/usr/local/bin'
```



## Dependencies

None.


## License

Public domain. See the [LICENSE file](LICENSE) for details.


## History

Rewritten from my pre-Galaxy version:

 - [docker-enabled-vagrant](https://github.com/William-Yeh/docker-enabled-vagrant).
 - [docker-host-tools](https://github.com/William-Yeh/docker-host-tools).

