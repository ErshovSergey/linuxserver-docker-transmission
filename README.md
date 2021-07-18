Обертка для https://github.com/linuxserver/docker-transmission

# Transmission
Параметры для запуска настраиваются в файле *.env* (переименовать *.env-default* в *.env*)  

### Запуск  
```
docker-compose up --build -d --remove-orphans --force-recreate
```

### Остановка  
```
docker-compose down --remove-orphans
```

### Рестарт
```
docker-compose up --build -d --remove-orphans --force-recreate
```

### Обновление 
```
docker pull linuxserver/transmission
```
