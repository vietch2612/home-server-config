# Ross's Home Server

A lightweight home server setup using Docker and Docker Compose for automation, network filtering, and container management.

## Services
| Service         | Description                  | Port    | Access URL                         |
|------------------|------------------------------|---------|-------------------------------------|
| Home Assistant   | Home automation platform    | 8123    | `http://<SERVER_IP>:8123`          |
| AdGuard Home     | Network-wide ad blocker     | 80, 53  | `http://<SERVER_IP>`               |
| Portainer        | Docker management UI        | 9000    | `http://<SERVER_IP>:9000`          |

