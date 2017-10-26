# Ansible Role: Unattended Upgrades

[![Build Status](https://travis-ci.org/markahesketh/ansible-role-unattended-upgrades.svg?branch=master)](https://travis-ci.org/markahesketh/ansible-role-unattended-upgrades)

Ansible role to manage Unattended Upgrades on Ubuntu/Debian systems.

## Installation

```
ansible-galaxy install markahesketh.unattended-upgrades
```

## Role Variables

Default values are listed below (see [`defaults/main.yml`](defaults/main.yml)):

```yml
unattended_upgrades_update_package_lists: 1
unattended_upgrades_download_upgradeable_packages: 1
unattended_upgrades_autoclean_interval: 7
unattended_upgrades_unattended_upgrade: 1
```

Refer to the [Unattended Upgrades documentation](https://wiki.debian.org/UnattendedUpgrades) for usage details.

## License

This role is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).

## Author

By [Mark Hesketh](https://www.markhesketh.co.uk/), a web developer from Manchester, UK.

* Blog: [markhesketh.co.uk](https://www.markhesketh.co.uk/)
* Twitter: [twitter.com/markahesketh](https://www.twitter.com/markahesketh/)
* GitHub: [github.com/markahesketh](http://www.github.com/heskethm/)
* Email: [contact@markhesketh.co.uk](mailto:contact@markhesketh.co.uk)
