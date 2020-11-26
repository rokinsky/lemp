# Basic LEMP Stack Setup

* Linux;
* nginx; 
* MySQL; 
* php
---
* adminer
* ftpd
* docker-compose

## Usage

```bash
mv .env.example .env
docker-compose up -d
```

### Applications

Add a new folder to `apps` equal to the domain name, for example `apps/your-domain.com`, and it will be available at `http://your-domain.com`.
