## Задание 1

Создание образа 

```bash
docker image build . --tag=netology_vorontsova 
```

Запуск контейнера 

```bash
docker run --name=netology_hw_vorontsova -d -p 7007:80 netology_vorontsova
```