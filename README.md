# symfony

### Run Docker containers

##### (LINUX only)

```
$ docker-compose up -d
```

##### (MAC only)

```
$ docker-sync start
$ docker-compose -f docker-compose.mac.yml up -d --build
```

### Install dependencies

```
$  docker exec -u www-data -it php-symfony bash
$ cd /var/www/html/
$ composer install
```