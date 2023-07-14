# Jaeger Playground

## Setup

```bash
# get the docker-compose file
wget https://raw.githubusercontent.com/jaegertracing/jaeger/main/examples/hotrod/docker-compose.yml

# start the docker-compose file
docker-compose up -d

# check the status of the docker-compose file
docker-compose ps
```

## Usage

* [Jaeger UI](http://localhost:16686/search)
* [Hotrod UI](http://localhost:8080)

## Cleanup

```bash
# stop the docker-compose file
docker-compose down
```

## References

* [Jaeger](https://www.jaegertracing.io/)
* [Demo](https://github.com/uber/jaeger/tree/main/examples/hotrod)
* [Medium Blog](https://medium.com/opentracing/take-opentracing-for-a-hotrod-ride-f6e3141f7941)