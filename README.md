# Welcome
Package Manger / Templated Application Repository

![image](https://user-images.githubusercontent.com/50801771/64287218-67b0e600-cf5f-11e9-8fe7-f36cb8e71f6f.png)

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

- [Deploy a Local Docker Swarm: bekkerstacks/docker-swarm](https://github.com/bekkerstacks/docker-swarm)
- [Deploy Traefik: bekkerstacks/traefik](https://github.com/bekkerstacks/traefik)
- [Deploy a Monitoring Stack: bekkerstacks/monitoring-cpang](https://github.com/bekkerstacks/monitoring-cpang)

The others:
- https://github.com/bekkerstacks?tab=repositories
