# MariaDB 10.1

MariaDB docker container

## Get Docker image
docker pull mariadb

## Hosting a Samba instance
docker run --name mariadb --restart=always -p 3306:3306 -v /var/lib/mysql:/var/lib/mysql -e MYSQL_ROOT_PASSWORD=??? -d mariadb:latest
