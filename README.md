# docker-php5.6-apache

A Debian LAMP container

It's on [docker-hub](https://hub.docker.com/repository/docker/niclab/php5.6/) and [github](https://github.com/Akito-K/docker-php5.6)

## tags and links
* `latest` [(main/Dockerfile)](https://github.com/Akito-K/docker-php5.6/blob/main/Dockerfile)

## how to build

```sh
git clone git@github.com:Akito-K/docker-php5.6.git
cd docker-php5.6
docker build --rm -t niclab/php5.6 .
```

## running

```sh
docker-compose up -d
```