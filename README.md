# Docker Nginx Proxy
##### JukeLabs

Authors: [Ryan Powszok](ryan@jukelabs.com)

Last Updated: 07/31/2018 Created: 07/31/2018

---

## Get Started

This repo contains a docker setup for using the JWilder Nginx Proxy. See https://github.com/jwilder/nginx-proxy for more info.

Make sure you have docker installed and running. Also make sure you don't have any running containers using port 80 or 443.

```
Git clone repo and cd into project folder. Run the following commands:
$ docker network create proxy
$ docker-compose up -d
```
