# HTB - Redeemer

## Что изучила

* Redis
* Порт 6379
* In-memory Database
* redis-cli

## Использованные команды

nmap -Pn <IP>

redis-cli -h <IP>

INFO

KEYS *

GET flag

## Что получилось

Подключилась к Redis серверу, получила информацию о сервере, просмотрела ключи базы данных и извлекла флаг из ключа flag.
