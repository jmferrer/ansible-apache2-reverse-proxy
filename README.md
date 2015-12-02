# ansible-apache2-reverse-proxy
Ansible playbooks to deploy an apache2 service as a reverse proxy with authentication and cache in Debian 8.

Exec as root: ansible-playbook -i "localhost," -c local site.yml

Detailed list of enabled modules:
- proxy related
  - alias
  - ratelimit
  - rewrite
  - headers
  - proxy_ajp
  - proxy_balancer
  - proxy_connect
  - proxy_express
  - proxy_ftp
  - proxy_html
  - proxy_http
  - proxy_scgi
  - proxy_wstunnel
  - ssl
  - vhost_alias
  - xml2enc
- auth related
  - auth_digest
  - authnz_ldap
  - ldap
- cache related
  - cache_disk
  - cache
  - file_cache
