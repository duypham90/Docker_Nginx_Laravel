# Docker
> Should read Docker with AWS (ECR/ECS), d CircleCI/Jenkins

## Build docker: 
- docker-compose up -d

## Stop container
- docker-compose stop

## exec container in docker

```
exec nginx
- docker exec -it nginx /bin/bash
```

```
exec mysql
- docker exec -it db /bin/bash
>> mysql -u root -p
```

