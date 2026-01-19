# TyFi Server

> **IP**: 188.245.209.158
> **Provider**: Hetzner
> **Purpose**: Personal automation, health tracking

## Access

```bash
ssh root@188.245.209.158
# See credentials in secure storage
```

## Services

| Service | URL/Port | Status |
|---------|----------|--------|
| n8n | https://n8n.tyfi.fyi | Active |
| Grafana | https://h.tyfi.fyi | Active |
| PostgreSQL | postgres:5432 | Active |
| InfluxDB | influxdb:8086 | Active |

## Databases

### PostgreSQL (tyfi)
- **Host**: postgres (container)
- **Database**: tyfi
- **User**: tyfi

### InfluxDB
- Health metrics time-series data

## Docker Containers

- n8n
- postgres
- influxdb
- grafana

## Webhooks

| Endpoint | Purpose |
|----------|---------|
| /webhook/capture-simple | iOS screenshot capture |
| /webhook/captures-review | Web review interface |
| /webhook/host-cmd | Server command execution |
| /webhook/pg-query | Direct PostgreSQL queries |
