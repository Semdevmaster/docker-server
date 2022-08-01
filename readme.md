# Быстрые команды

## Скачать исходники
Находясь в терминале, в корне проекта  
```
degit https://github.com/Semdevmaster/docker-server . --force
```

## Установка Laravel
Находясь в терминале, в корне проекта  
```
make install-laravel
```

## Установка MODX
Находясь в терминале, в корне проекта
```
make install-modx
```

## Сделать бэкап MySQL
Находясь в терминале, в корне проекта
```
make mysql-backup
```

## Сгенерировать SSL сертификаты для проекта
Находясь в терминале, в папке server/nginx/ssl
```
mkcert site.loc www.site.loc localhost 127.0.0.1 ::1 192.168.1.6
```
