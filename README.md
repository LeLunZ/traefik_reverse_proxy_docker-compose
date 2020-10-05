# Traefik Service as docker-compose


## Installation

* Clone this repo
* change traefik.toml
* change docker-compose.yaml
* chmod 600 acme.json
* start the container
* use the traefikNetwork defined in docker-compose.yaml in other docker-compose files.
* you are good to go


# Migrating to Traefik V2 
(which is highly recommended, because it performs better and provides more features)

Use this repo:
https://github.com/LeLunZ/traefik_reverse_proxy_docker-compose-v2

with these new middlewares and the migration guide:

https://doc.traefik.io/traefik/v2.2/middlewares/overview/

https://doc.traefik.io/traefik/migration/v1-to-v2/

* dont forget to change your existing docker-compose files to use the new traefik
