# Docker Flask OCR app with Celery ,  Redis

A basic [Docker Compose](https://docs.docker.com/compose/) template for orchestrating a [Flask](http://flask.pocoo.org/) application & a [Celery](http://www.celeryproject.org/) queue with [Redis](https://redis.io/)


### Installation

```bash
git clone https://github.com/nyamba/ocr-api.git
```

### Build & Launch

```bash
docker-compose build && docker-compose up -d 
```



To shut down:

```bash
docker-compose down
```
Request:
```
https://localhost:5000/?file_key=WTf/pdf
```


To change the endpoints, update the code in [app.py](app.py)
---

MORE [http://allynh.com/blog/flask-asynchronous-background-tasks-with-celery-and-redis/]
