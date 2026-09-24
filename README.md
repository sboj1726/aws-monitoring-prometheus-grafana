# AWS Monitoring with Prometheus and Grafana

Portfolio monitoring stack demonstrating Prometheus metric collection and Grafana dashboards.

## Architecture
Application / Node Exporter -> Prometheus -> Grafana -> Alerting

## Run
```bash
docker compose up -d
```

- Prometheus: http://localhost:9090
- Grafana: http://localhost:3000

Default demo credentials in Compose are for local learning only. Change them before any shared deployment.
