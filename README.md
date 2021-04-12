# Services RMS

Конфигурация Docker Compose для курса Ruby Microservices.

# Зависимости

+ Docker `19.03+`
+ Docker Compose `1.27+`

# Сервисы

+ RabbitMQ
+ Filebeat
+ Elasticsearch
+ Kibana

# Установка и запуск сервисов

1. Склонируйте репозиторий:

```
git clone git@github.com:avbelyshev/services-rms.git && cd services-rms
```

2. Запустите сервисы:

```
docker-compose up -d
```

Для запуска отдельного сервиса используйте команду:

```
docker-compose up -d <service_name>
```
