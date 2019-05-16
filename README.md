# Ansible FreeIPA Replica Role

This is just a dev repo for configuring a FreeIPA replica on CentOS 7.5


## Required Environment Variables

** NOTE: ** Be sure to set these to your own values. This is just a sample.

```
export HOSTNAME="localhost"   # Make this something meaningful, ie: "replica1" or "us-west2-replica1"
export IPASERVER_HOSTNAME="ipa"
export IPASERVER_IPADDRESS="1.2.3.4"
export DOMAIN="mydomain.local"
export IPA_JOIN_USER="admin"
export IPA_JOIN_PASS="SomeSuperSecretPassw0rd123"
```

| Environment Variable | Description |
| ------------- | ------------- |
| HOSTNAME      | this is the hostname of the replica host |
| IPASERVER_HOSTNAME | this is the hostname of the primary DC you wish to replicate |
| IPASERVER_IPADDRESS | this is the ip address of the primary DC you wish to replicate |
| DOMAIN | this is the domain you are joining |
| IPA_JOIN_USER | this is the username you are using to auth the join request |
| IPA_JOIN_PASS | this is the password you are using to auth the join request |

