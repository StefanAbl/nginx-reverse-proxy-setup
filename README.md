# nginx-reverse-proxy-setup
 
## Prequisits
install ansible and git
Generate ssh key for authentication with dynv6.com
add this key to dynv6.com
place the required variables in /root/vars.yaml
```
---
# The ip address the host name should point to
ip: 
# The record e.g. service
record:
# The host name e.g. host.dynv6.net
host: 
# The ip the reverse proxy should point to
service_ip:
```

## Code
```
apt-get update
apt-get install ansible git nano
ssh-keygen -f "/root/.ssh/dynv6" -t ssh-ed25519 -N ''
cat /root/.ssh/dynv6.pub
nano /root/vars.yaml
```
