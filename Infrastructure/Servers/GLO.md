# GLO Server

> **IP**: 165.232.155.105
> **Provider**: DigitalOcean
> **Purpose**: Business automation, Agent-OS

## Services

| Service | URL/Port | Status |
|---------|----------|--------|
| n8n | https://n8n.glo.tools | Active |
| Grafana | https://dash.glo.tools | Active |
| PostgreSQL | maestro-postgres:5432 | Active |
| Agent-OS v3 | /opt/agent-os-v3/ | Active |

## Databases

### PostgreSQL (maestro)
- **Container**: maestro-postgres
- **Database**: agent_os_v3
- **User**: maestro

## Agent-OS v3 Status

- **Tasks Complete**: 142
- **Success Rate**: ~69%
- **Location**: /opt/agent-os-v3/

## Webhooks

| Endpoint | Purpose |
|----------|---------|
| /webhook/agent-os | Agent-OS task execution |
| /webhook/claude-router | Claude routing |

## Key Paths

```
/opt/agent-os-v3/       # v3 Python system
/opt/agent-os/work/     # Git repositories
```
