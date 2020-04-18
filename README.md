# sonarqube-postgres
docker-compose files for SonarQube with PostgreSQL

## How to set up 

Install docker and docker compose.

You can set the recommended values as follows.
```
sysctl -w vm.max_map_count=26144
sysctl -w fs.file-max=65536
ulimit -n 65536
ulimit -u 4096
```

then, start containers as follows.
```
docker-compose up -d
```

