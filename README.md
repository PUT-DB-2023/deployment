# PUT-DB-2023 Deployment

This repository contains the configuration necessary to run the PUT-DB-2023 as a whole, using Docker & Docker Compose and NGINX as a web server + reverse proxy.

## Prerequisites
In order to run the system, the following tools are necessary:
- Docker
- Docker Compose
## Build and run
The following command builds the necessary Docker Images and runs the application.
```
docker-compose up --build
```
After successfully building and running the application, it can be accessed via a browser at `localhost` or `localhost:80`. The ports can be changed by modifying the appropriate lines in `docker-compose.yml` and `nginx.conf` configuration files.
