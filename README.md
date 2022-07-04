# Simple Python Flask Dockerized Application

[![Build Docker Image](https://github.com/rhodinemma/flask-docker/actions/workflows/build.yml/badge.svg)](https://github.com/rhodinemma/flask-docker/actions/workflows/build.yml)

Build the image using the following command

```bash
$ docker build -t simple-flask-app:latest .
```

Run the Docker container using the command shown below.

```bash
$ docker run -d -p 5000:5000 simple-flask-app
```

The application will be accessible at http:127.0.0.1:5000
