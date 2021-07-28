# raspi-monitoring
Prometheus and Grafana Raspberry Pi monitoring setup using Docker-Compose

## Setup
Ensure that Docker and Docker-Compose are both installed and on their latest version. Clone the repo onto your device (only tested on Raspberry Pi 4 Model B 8GB).
Within the root directory of the repo create the folders `prometheus` and `grafana` then run `sudo docker-compose up -d` to run the containers.
Finally go to `127.0.0.1:3000` to access the grafana interface (or whatever ip your device is accessible on the LAN)
