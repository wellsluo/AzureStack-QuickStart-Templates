# Create a Virtual Machine from a User Image

## Description
Deploys a VM using custom managed image which has been previously created.

This template also deploys a Virtual Network (with the appropriate DNS setting for the Azure Stack POC environment), Public IP address, Network Security Group, and a Network Interface.

## Change
- 2019-11
  - Update creating VM with managed disks from managed custom image.
  - Rename original deployment template to azuredeploy-unmanagedDisk.json.