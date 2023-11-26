# UberExporters
Prometheus exporter implementations

# Registries:

- [Dockerhub](https://hub.docker.com/)

# Docker images:

|  Image      | Registry                                                                     |
|-------------|------------------------------------------------------------------------------|
| Grafana     |    https://hub.docker.com/repository/docker/dejanualex/grafana/general       |
| Prometheus  |                                                                              |

* Start setup locally:

```bash
# check setup
docker-compose -f docker-compose config
# foreground
docker-compose -f docker-compose.yaml up
# background
docker-compose -f docker-compose.yaml up -d
```