# Security
Ansible ssh server role

## Requirements
Ansible version => 2.2

## Role tags:

# Vars
## Default role variables
```yaml
port: 22
listen_address: '0.0.0.0'
permit_root_login: 'without-password'
gateway_ports: 'no'
subsystem_sftp: 'internal-sftp -f AUTH -l VERBOSE'
```
