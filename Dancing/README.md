# HTB - Dancing

## Что изучила

* SMB (Server Message Block)
* Порт 445
* Общие папки Windows (Shares)
* Инструмент smbclient

## Использованные команды

nmap -Pn <IP>

smbclient -L <IP>

smbclient //IP/WorkShares

ls

cd

get flag.txt

## Что получилось

Нашла доступную SMB-шару WorkShares, просмотрела файлы, скачала flag.txt и получила флаг.
