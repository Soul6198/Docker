## Задание 2 

Запуск контейнера: 

1. Собрать образ командой 
```bash
docker image build rest_api_container/ --tag=popov.ao4
```
2. Запустить контейнер командой 
```bash
docker run --name=popov.ao4_2 -d -p 6060:6060 popov.ao4
```
