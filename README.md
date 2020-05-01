## Description

Sample Docker setup for React using create-react-app with Enivronment (Dev and Prod) handling and CI/CD using TravisCI and AWS Elastic Beanstalk while nginx is used as server for Prod environment.

## To start Development server

```bash
# Have docker installed
$ docker-compose up --build
# Listening on 3000
```

## To run Prod build

```bash
# Building and running the docker image
$ docker build -t react .
$ docker run -p 8080:80 react
# Listening on 8080
```
