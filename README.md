# zabbix-check-disk-performance

## Description

A script to monitor the disk performance with [Zabbix](https://zabbix.com).

## Usage

* Clone this repo and build the debian package yourself with `LANG=C debuild -us -uc -b; dh clean`
**or**
* Install it directly from @istoph's [repository](https://blog.chr.istoph.de/repository/)
**or**
* Clone this repo and install the script and config by hand

## Dependencies

* Python

## Licence

MIT License (see [debian/copyright](debian/copyright))

## Template for the Zabbix frontend

A template for the Zabbix frontend can be found, as usual in our packages, in [/usr/share/doc/${package_name}/](usr/share/doc/zabbix-check-disk-performance/)

