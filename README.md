# Networkdev Machine [![Build Status](https://travis-ci.com/niksheridan/networkdev.svg?branch=master)](https://travis-ci.com/niksheridan/networkdev)

Development Machine for Network Engineers.

## Versions

Testing provisioning playbooks for:

* Centos
* Debian

Ubuntu may need to be added to this for testing.

## Execution on Windows

A companion VM could be deployed that would run a playbook on the actual VM to be used.  
This might work around the problem not being able to run ansible on the host if it is
windows.

Futher investigation into this aspect is in progress (such as running the role directly
on the VM itself)