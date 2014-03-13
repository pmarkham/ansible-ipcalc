ansible-ipcalc
==============

Ansible IP calc module. Given an IP address and netmask, return a bunch of facts that can be used by other tasks in the playbook.

Facts returned are:

* ipcalc_ip_addr
* ipcalc_netmask
* ipcalc_subnet
* ipcalc_netmask_bits
* ipcalc_network
* ipcalc_broadcast_addr
* ipcalc_host_min
* ipcalc_host_max
* ipcalc_num_hosts
