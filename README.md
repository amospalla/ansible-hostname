# ansible-hostname
* * *

## Description

Sets a host's hostname.

On RedHat OS family also sets the HOSTNAME variable on /etc/sysconfig/network file.

Hostname is taken from {{ inventory_hostname }} but that can be overriden with the variables _hostname_custom_ and _hostname_custom_short_.

## Variables

Optional:
- _hostname_custom_: use this variable for hostname instead of _inventory_hostname_.
- _hostname_custom_short_: use this variable for hostname instead of the first token from either _inventory_hostname_ or _hostname_custom_.
