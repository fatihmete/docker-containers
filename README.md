# docker-containers
Docker container CLI commads

# Docker
## Bridge network

````
docker network create -d bridge airflow_network
````

# Mysql

## arm64

````
docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d arm64v8/mysql
````
