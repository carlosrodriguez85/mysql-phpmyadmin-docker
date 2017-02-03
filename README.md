# mysql-phpmyadmin-docker

A docker-compose image to generate a container for MySQL and phpMyAdmin.

## Usage

- Clone git repository
```
# git clone https://github.com/carlosrodriguez85/mysql-phpmyadmin-docker.git
# cd mysql-phpmyadmin-docker
```

- Configure ports
Edit the "ports" section in "docker-compose.yml" file in order to setup which ports are going to be used by MySQL and phpMyAdmin. By default, phpMyAdmin will use port 8080 and MySQL 3306. You can also setup a custom root password for MySQL through the MYSQL_ROOT_PASSWORD variable.

- Run docker-compose
```
# docker-compose up
```

## Acknowledgements

http://stackoverflow.com/questions/39054411/docker-connecting-phpmyadmin-to-mysql-doesnt-work
