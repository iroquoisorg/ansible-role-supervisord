# supervisord

[![Build Status](https://travis-ci.com/iroquoisorg/ansible-role-supervisord.svg?branch=master)](https://travis-ci.com/iroquoisorg/ansible-role-memcached)

Ansible role for supervisord

This role was prepared and tested for Ubuntu 16.04.

# Installation

`$ ansible-galaxy install iroquoisorg.supervisord`

# Default settings

```

supervisor_config: '/etc/supervisor/supervisord.conf'
supervisor_conf_dir: '/etc/supervisor/conf.d/'
supervisor_log_dir: "/var/log/supervisor/"
supervisor_pid_dir: "/var/run/supervisor/"
supervisor_user: "www-data"
supervisor_group: "www-data"
supervisor_tasks: []

```
