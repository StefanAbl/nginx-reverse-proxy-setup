# nginx-reverse-proxy-setup
 
## Prequisits
install ansible and git
Generate ssh key for authentication with dynv6.com
add this key to dynv6.com

## Code
```
apt-get update
apt-get install ansible git
ssh-keygen -f "/root/.ssh/dynv6" -t ssh-ed25519 -N ''
```
