# Multiple VM Availability Set

## Description
Deploys a set of Linix VM´s (centos ) as part of the same availability set. This template template also deploys an availability set, a virtual Network (with DNS), a load balancer with a front end Public IP address, and a Network Security Group.
VM´s require the following Deployed Ubuntu Images:
* osImagePublisher: _Canonical_ 
* osImageOffer: _UbuntuServer_
* osImageSKU: _18.04-LTS_


## Change

- 2019-11: 
  - Update template to support managed disk. 
  - Fix the issue that multiple VMs use same OS disk name. 

