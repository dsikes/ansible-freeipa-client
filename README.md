# Ansible FreeIPA Replica Role

This is just a dev repo for configuring a FreeIPA replica on CentOS 7.5


## Required Environment Variables

** NOTE: ** Be sure to set these to your own values. This is just a sample.

```
export HOSTNAME="localhost"
export IPASERVER_HOSTNAME="ipa"
export IPASERVER_IPADDRESS="1.2.3.4"
export DOMAIN="mydomain.local"
export IPA_JOIN_USER="admin"
export IPA_JOIN_PASS="SomeSuperSecretPassw0rd123"
```