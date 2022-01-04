# RabbitMQ

## Run RabbitMQ

```bash
cd rabbitmq
docker-compose up -d
```

## Access to RabbitMQ

http://localhost:15672/

user & password: guest

## Integrate

### Golang application

#### Publisher

```sh
go run consumer/consumer.go
```

#### Consumer

```sh
go run sendMessage/sendMessage.go
```

## REF

https://x-team.com/blog/set-up-rabbitmq-with-docker-compose/
