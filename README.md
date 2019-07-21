# Welcome
Package Manger / Templated Application Repository

## About

The idea is to have a package manager for docker swarm applications

Idea:

```
$ bstacks list --category monitoring
monitoring-cpang (cAdvisor, Prometheus, AlartManager, NodeExporter, Grafana)
monitoring-tick  (Telegraf, InfluxDB, Chronograf, Kapacitor)
...
```

Deploy:

```
$ bstacks deploy --stack-name monitoring-cpang --name-space mon
Deploying monitoring-cpang
mon_prometheus
mon_grafana
...
```

## More

- [Deploy a Local Docker Swarm](https://github.com/bekkerstacks/docker-swarm)
- [Deploy Traefik](https://github.com/bekkerstacks/traefik)
- [Deploy a Monitoring Stack](https://github.com/bekkerstacks/docker-swarm)
