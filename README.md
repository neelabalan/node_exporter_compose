# node_exporter_compose

> A docker-compose example to monitor a local computer with Grafana, Prometheus and node-exporter

Using [this repository](https://github.com/epfl-dojo/monitoringrafana) as base. The only difference is `grafana` version `8.1.1` is used in this case since I ran into [this issue](https://discuss.linuxcontainers.org/t/bad-data-1-parse-error-bad-duration-syntax-1m0-error-in-grafana/13350/10) with the original repo.
