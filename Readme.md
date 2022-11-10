**If you want to build multiple docker images at once you could use docker compose :**

Just specify few docker images in doker-compose.yaml file, and you could build them and run simultaneously without bash scripting

Install docker-compose: https://docs.docker.com/compose/install/other/

call: `docker-compose up -d`

Than look for your containers: `docker ps`
