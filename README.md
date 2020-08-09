# Installation

This app uses docker to encapsulate the required services. Please ensure that [docker-compose](https://docs.docker.com/compose/install/) is installed.

### Development Mode:

To start all services and run the django app with interactive shell:

```python3
docker-compose -f docker-compose.yml -f docker-compose.dev.yml up -d
docker attach app`
```
