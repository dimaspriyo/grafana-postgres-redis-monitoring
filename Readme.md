
## Preview Of Postgres Monitoring Dashboard
![Preview Postgres Monitoring Dashboard.](https://github.com/dimaspriyo/grafana-postgres-redis-monitoring/screenshoots/postgres-dashboard.png)

## Preview Of Redis Monitoring Dashboard
![Preview Redis Monitoring Dashboard.](https://github.com/dimaspriyo/grafana-postgres-redis-monitoring/screenshoots/redis-dashboard.png)


## How To
1. docker exec -i postgres psql -U postgres -d pagila_db < pagila-schema.sql
2. docker exec -i postgres psql -U postgres -d pagila_db < pagila-insert-data.sql
3. For Trigger redis activity using:  **docker exec -it redis redis-benchmark -h redis -p 6379 -q -n 100000 -c 50 -P 16**


### Reference Links
- https://github.com/devrimgunduz/pagila (Postgres Dataset)
- ChatGPT
- https://grafana.com/grafana/dashboards/11835-redis-dashboard-for-prometheus-redis-exporter-helm-stable-redis-ha/
- https://grafana.com/grafana/dashboards/9628-postgresql-database/