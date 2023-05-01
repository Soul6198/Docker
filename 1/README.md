## Задание 1

Создание образа:

```
docker image build . --tag=my_app
```

Запуск контейнера:

```
docker run --name=my_app_1 -d -p 7007:80 my_app
```