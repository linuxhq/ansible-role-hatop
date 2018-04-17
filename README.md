# ansible-role-hatop

[![Build Status](https://travis-ci.org/linuxhq/ansible-role-hatop.svg?branch=master)](https://travis-ci.org/linuxhq/ansible-role-hatop)
[![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-hatop-blue.svg?style=flat)](https://galaxy.ansible.com/linuxhq/hatop)
[![License](https://img.shields.io/badge/license-GPLv3-brightgreen.svg?style=flat)](COPYING)

RHEL/CentOS - Interactive ncurses client for HAProxy

## Requirements

None

## Role Variables

None

## Dependencies

 * https://galaxy.ansible.com/linuxhq/linuxhq

## Example Playbook

    - hosts: servers
      roles:
        - linuxhq.hatop

## License

Copyright (C) 2018 Taylor Kimball <tkimball@linuxhq.org>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <http://www.gnu.org/licenses/>.
