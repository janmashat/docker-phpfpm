docker-phpfpm
==============

Docker image for php-fpm on Debian 8 (jessie)

Based on: https://hub.docker.com/r/jonathonf/debian-phpfpm/~/dockerfile/

### How to use:

```sh
git clone https://github.com/janmashat/docker-phpfpm.git
cd docker-phpfpm

docker build -t phpfpm .
docker run --name fpm -v $HOME/html:/var/www/html phpfpm
```
