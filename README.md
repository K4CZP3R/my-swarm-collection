# my-swarm-collection
My collection of docker swarm modules


## Modules

### DNS

> DNS server to resolve custom domains to ips on my local network

### Flame

> My homepage with apps and bookmarks

### rpi-system-info

> My "cluster" is based on multiple raspberries with i2c lcd. This module shows node info

### swarmpit

> Manager of my swarm

### uptime-kuma

> Status page of my services

## Things left to do

- [ ] Implement NAS to centralize storage between nodes
  - [ ] GlusterFS
  - [ ] NAS on external server (avoid microsd on pi)
- [ ] Improve deploy_it script
- [ ] Do i need to expose ports even when in internal network?
