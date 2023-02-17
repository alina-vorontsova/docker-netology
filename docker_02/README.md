## Задание 2 

Запуск контейнера: 

1. Заменить при необходимости значение переменных в файле `rest_api_container/stocks_products/.env`
2. Собрать образ командой 
```bash
docker image build rest_api_container/ --tag=netology_vorontsova2
```
3. Запустить контейнер командой 
```bash
docker run --name=netology_vorontsova2_1 -d -p 6060:6060 netology_vorontsova2
```
