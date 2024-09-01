# pymongo-api

## Как запустить

Запускаем mongodb и приложение

```shell
cd ./sharding-repl-cache
docker compose up -d
```

Заполняем mongodb данными

```shell
sudo chmod +x ./mongo-init.sh && ./mongo-init.sh
```

Наблюдать результать можно в браузере:  
[http://localhost:8080](http://localhost:8080)

Свагер:  
[http://localhost:8080/docs](http://localhost:8080/docs)

