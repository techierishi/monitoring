## Monitoring base

```bash
mkdir -p grafana/provisioning
touch grafana.ini
docker-compose up -d
```

### For apply changes grafana.ini 

```bash
docker-compose restart grafana
```