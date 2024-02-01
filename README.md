## Monitoring base

```bash
mkdir -p grafana/provisioning
docker-compose up -d
```

### For apply changes grafana.ini 

```bash
docker-compose restart grafana
```