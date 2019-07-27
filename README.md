# docker-mysql

## pre-requirements

- Centos 7
- docker 18.09 with docker swarm

## create_mysql.sh

```bash
MYSQL_ROOT_PASSWORD=''
NFS_HOST=''
NFS_PATH=''
docker stack deploy -c docker-compose.yml stack_mysql
```
