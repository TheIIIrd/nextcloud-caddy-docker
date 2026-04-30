# Nextcloud Caddy Docker
Preconfigured Docker container with Nextcloud and Caddy to create your own home cloud storage

## How to install
1. Environment preparation:
   ```bash
   sudo apt update && sudo apt install git docker.io docker-compose docker-doc -y 
   git clone git@github.com:TheIIIrd/nextcloud-caddy-docker.git && cd ./nextcloud-caddy-docker/
   bash -c 'mkdir -p ./{db_data,redis_data,nextcloud_data,nextcloud_config,nextcloud_custom_apps,caddy_data,caddy_config}'
   ```

2. Setting password:
   ```bash
   nano .env 
   ```

3. Launching Docker containers:
   ```bash
   sudo docker compose up -d 
   ```
