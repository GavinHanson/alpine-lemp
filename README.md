## Quick Start
To use:
```
docker run -d \
--name lemp \
-p 80:80 \
-p 3306:3306 \
-e MYSQL_ROOT_PASSWORD=<SQL PASSWORD> \
-v /Users/gavin/Projects/docker/docker-nginx-php-mysql/tmp/mysql:/var/lib/mysql \
-v /Users/gavin/Projects/docker/docker-nginx-php-mysql/tmp/www_data:/var/www/html \
934f37d16ebf
```