# Ansible Role: memcached

[![Build Status](https://travis-ci.org/arillso/ansible.memcached.svg?branch=master)](https://travis-ci.org/arillso/ansible.memcached) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-memcached-blue.svg)](https://galaxy.ansible.com/arillso/memcached)

## Description

## Installation

```bash
ansible-galaxy install arillso.memcached
```

## Requirements

None

## Role Variables

| Variable | Default | Comments (type) |
| :--- | :--- | :--- |
| ```memcached_host``` | ```0.0.0.0``` | Address to listen for connections |
| ```memcached_port``` | ```11211``` | Port to listen for connections |
| ```memcached_max_conn``` | ```512``` | |
| ```memcached_cache_size``` |  ```64``` | Max memory to use in megabytes |
| ```memcached_fs_file_max``` | ```756024```| |
| ```memcached_options``` | | |
| ```memcached_user``` | ```memcache``` | |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - arillso.memcached
```

## Changelog

### 1.0

* initial commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher