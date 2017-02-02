# Ansible Role: ansible-role-stack

Meta role to require all the common roles and versions used by Druid infras.

See [changelog](CHANGELOG.md) for changes.

## How to use in infra project:

Add this to requirements.yml:

```
- src: git@github.com:druidfi/ansible-role-stack.git
  scm: git
  version: 1.0.0
  name: druidfi.role-stack
```

No need to add this role to any playbook, as you will use the roles below in your playbooks.

## Roles included:

- alekseyp.papertrail
- druidfi.nginx-includes
- druidfi.nginx-certbot-cert
- geerlingguy.certbot
- geerlingguy.composer
- geerlingguy.daemonize
- geerlingguy.drush
- geerlingguy.firewall
- geerlingguy.git
- geerlingguy.java
- geerlingguy.mailhog
- geerlingguy.memcached
- geerlingguy.mysql
- geerlingguy.nodejs
- geerlingguy.php
- geerlingguy.php-memcached
- geerlingguy.php-mysql
- geerlingguy.php-pecl
- geerlingguy.php-xdebug
- geerlingguy.postfix
- geerlingguy.repo-epel
- geerlingguy.repo-remi
- geerlingguy.ruby
- geerlingguy.security
- geerlingguy.solr
- geerlingguy.varnish
- jdauphant.nginx
- jdauphant.ssl-certs
