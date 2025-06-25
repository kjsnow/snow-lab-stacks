# snow-lab-stacks
Compose files for docker container stacks managed by dockge

## Setup
- In the `/opt` dir create a `dockge` dir
- Copy the `compose.yaml` file from this repo to `/opt/dockge`

```
sudo mkdir -p /opt/dockge
sudo cp dockge-setup/compose.yaml /opt/dockge
cd /opt/dockge
sudo docker compose up -d
```