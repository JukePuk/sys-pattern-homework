# Домашнее задание к занятию "`Заббикс Часть 1`" - `Панков Александр Алексеевич`


### Задание 1

`Приведите ответ в свободной форме........`

1. ![alt text](https://github.com/JukePuk/sys-pattern-homework/blob/main/Снимок%20экрана%202023-12-28%20в%2016.30.51.png)
2. `get https://repo.zabbix.com/zabbix/6.4/ubuntu/pool/main/z/zabbix-release/zabbix-release_6.4-1+ubuntu22.04_all.deb`
<br>`dpkg -i zabbix-release_6.4-1+ubuntu22.04_all.deb`
<br>`apt update`
<br>`apt install zabbix-server-pgsql zabbix-frontend-php php8.1-pgsql zabbix-apache-conf zabbix-sql-scripts zabbix-agent`
<br>`sudo -u postgres createuser --pwprompt zabbix`
<br>`sudo -u postgres createdb -O zabbix zabbix`
<br>`zcat /usr/share/zabbix-sql-scripts/postgresql/server.sql.gz | sudo -u zabbix psql zabbix`
<br>`systemctl restart zabbix-server zabbix-agent apache2`
<br>`systemctl enable zabbix-server zabbix-agent apache2`

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота 1](ссылка на скриншот 1)`


---

### Задание 2

`Приведите ответ в свободной форме........`

1. ![alt text](https://github.com/JukePuk/sys-pattern-homework/blob/main/Снимок%20экрана%202023-12-28%20в%2016.33.12.png)
2. ![alt text](https://github.com/JukePuk/sys-pattern-homework/blob/main/Снимок%20экрана%202023-12-28%20в%2016.33.30.png)
3. ![alt text](https://github.com/JukePuk/sys-pattern-homework/blob/main/Снимок%20экрана%202023-12-28%20в%2016.35.25.png)

