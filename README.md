## Clickhouse Metabase Docker

## 1. Install docker and docker compose
```bash
sudo apt update
sudo apt install curl -y
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo apt-get install docker-compose-plugin
```
## 2. Run
```bash
sudo docker compose up --build -d
```