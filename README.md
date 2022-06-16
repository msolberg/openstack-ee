# openstack-ee
OpenStack Execution Environment for Ansible

This repository contains the files used to build the openstack execution environment available at https://quay.io/repository/msolberg/ee-openstack-rhel8.

## Building your own image

To build your own execution environment using these files with ansible-builder, clone this repository, and use the following command at the top level directory: 

```
ansible-builder build -t openstack-ee:latest
```

## Documentation

For documentation on ansible-builder, see the following:

https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/2.1/html/ansible_builder_guide

