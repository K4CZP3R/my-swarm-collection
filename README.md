# my-swarm-collection

My collection of docker swarm modules

## Modules

### DNS

> DNS server to resolve custom domains to ips on my local network

![Example of the swarmpit page](repo_assets/dns_example.png?raw=true)

### Flame

> My homepage with apps and bookmarks

![Example of the swarmpit page](repo_assets/flame_example.png?raw=true)

### rpi-system-info

> My "cluster" is based on multiple raspberries with i2c lcd. This module shows node info

![Example of the swarmpit page](repo_assets/rpi-system-info_example.jpeg?raw=true)

### swarmpit

> Manager of my swarm

![Example of the swarmpit page](repo_assets/pit_example.png?raw=true)

### uptime-kuma

> Status page of my services

![Example of the uptime-kuma status page](repo_assets/kuma_example.png?raw=true)

## Things left to do

- [ ] Implement NAS to centralize storage between nodes
  - [ ] GlusterFS
  - [ ] NAS on external server (avoid microsd on pi)
- [ ] Improve deploy_it script
- [ ] Do i need to expose ports even when in internal network?
