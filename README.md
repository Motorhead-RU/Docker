# Docker

#### Создать образ:
```
docker build . --file Dockerfile --tag image-tag
```


#### Запустить образ

```
docker run image_id/image_tag
```

#### Открыть терминал в контейнере:

```
docker exec -it container_id /bin/sh
```

#### Показать список образов:

```
docker images
```
```
docker image -ls
```
#### Показать список работающих контейнеров:

```
docker ps
docker ps -a 
```

#### Удаление

+ Удалить образ:

```
docker rmi image_id
```

+ Удалить контейнер:

```
docker rm container_id
```

+ Удалить все неиспользуемые контейнеры, сети и образы:

```
docker system prune -a
```
