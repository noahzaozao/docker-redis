# docker-redis

## pre-requirements

- Centos 7
- docker 18.09 with docker swarm

## create_redis.sh

```bash
REDIS_PASS=''
docker stack deploy -c docker-compose.yml stack_redis
```
