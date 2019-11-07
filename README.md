Ansible Role: lldpd
===================

Installs the lldpd package on a linux host.

Tested OS
---------
Ubuntu 18.04.1

Variables
---------
| variable          | default  | description                       |
| ----------------- | -------- | --------------------------------- |
| lldpd_interfaces  | enp0     | interface pattern to match        |
| lldpd_cdp         | enabled  | cdp on/off                        |
| lldpd_cdp_version | v2       | cdp version                       |
| lldpd_portid      | ifname   | portid subtype to advertise       |
