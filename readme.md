# Simple NGINX configuration with multiple


This configuration is used for multi website configurion on single server

## Requirement

All IP Address dedicated to server must be accessible.

If running  UBUNTU VM use reference: to add secondary nics

https://gist.github.com/ThomasLeister/640812441505447ba8f19f85314fbf5b

Sample - config provided

1- edit the /etc/netplan/50-cloud-init.yaml
2- add all the private ip address. Do not need to add primary nic.
3- to apply config - run netplan try

