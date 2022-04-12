### A pretty simplified Docker Compose workflow that sets up a LEMP network of containers for local Laravel development:
## - php-fpm(version 8.1)
## - nginx(version latest)
## - mysql(version 8.0)
## - redis(version latest)

##Extra supported extensions php
- **redis**
- **mbstring**
- **pdo_mysql**
- **zip**
- **exif**
- **pcntl**
- **gd**
- **opcache**
- **intl**

To get started, make sure you have [Docker installed](https://docs.docker.com/get-docker/) on your system, and then clone this repository.

Next, navigate in your terminal to the directory you cloned this, and spin up the containers for the web server by running `docker-compose up -d`.

###Used ports on your system:
- **nginx** - `:80`, `:443`
- **mysql** - `:9306`
- **php-fpm** - `:9000`
- **redis** - `:9379`