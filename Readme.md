# Ansible Role: Mailcatcher

An Ansible Role that installs Mailcatcher.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

Set this to true to install the Ruby 1.9.3 package:

~~~
mailcatcher_install_ruby: false
~~~

Mailcatcher ports and IPs:

~~~
mailcatcher_http_ip: 0.0.0.0
mailcatcher_http_port: 1080
mailcatcher_smtp_ip: 0.0.0.0
mailcatcher_smtp_port: 1025
~~~

## Dependencies

* Ruby (optional) If ruby isn't installed already, the role can install Ruby 1.9.3

## Example Playbook

    - hosts: search
      roles:
        - ansible-role-mailcatcher

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Jrgns](http://jrgns.net), maintainer of [EagerELK](http://eagerelk.com).
