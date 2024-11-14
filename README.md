# Coderoom Judge

```
git clone https://github.com/nileshphapale142/coderoom-judge.git
cd coderoom-judge
mv judge0.template.conf judge0.conf
```
- Add REDIS_PASSWORD and POSTGRES_PASSWORD in judge0.conf
```
docker-compose up -d db redis
sleep 10s
docker-compose up -d
sleep 5s
```
