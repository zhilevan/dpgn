# Django, Postgres, Gunicorn and Nginx Docker image
Django, Postgres, Gunicorn and Nginx Package to building a micro service


This is Docker Image which provided as Python( Djnago) microservice with postgres as database , greenunicorn as python web service interface and Nginx as web service.

## How to use
**Note: The instructions below assumes you have [docker](https://docs.docker.com/engine/installation/) and [docker-compose](https://docs.docker.com/compose/install/) installed.**
- Download scripts
```
# git clone https://github.com/zhilevan/dpgn
# cd dpgn
```
- Build images
```
# docker-compose up --build
```

- Run Micro Service (as Daemon)

```
# docker-compose up -d
```

Read more in Documenation page [Basic micro service based on Django-Posgres-Gunicorn-Nginx](http://zhilevan.com/en/blog/Basic-micro-service-based-Django-Posgres-Gunicorn-Nginx)
