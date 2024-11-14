# Coderoom Judge

- Clone repo
- Moved to the directory
- Rename "judge0.template.conf" to "judge0.conf"
- Add REDIS_PASSWORD and POSTGRES_PASSWORD in "judge0.conf"
- Run following commands
```
docker-compose up -d db redis
sleep 10s
docker-compose up -d
sleep 5s
```