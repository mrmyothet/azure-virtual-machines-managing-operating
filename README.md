# Managing and Operating Azure Virtual Machines

```
az login

az account set -s MySubscription

az vm list-vm-resize-options -g resource-group-vm -n ubuntu-server-on-azure --query [].name
```
