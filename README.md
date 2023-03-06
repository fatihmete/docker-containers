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

# Airflow

## arm64
````
docker run --rm -it --name airflow --platform linux/arm64 -p 8080:8080 -e AIRFLOW_UID=1000 -u root --network airflow_network apache/airflow:latest bash
````
