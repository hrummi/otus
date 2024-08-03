Запустил инсталляцию wordpress, подготовленную для предыдущих заданий.
Развернул с помощью docker compose Telegraf, Influxdb, Chronograf, Kapacitor. Для Telegraf отдельный docker compose.

Произвёл первичную настройку Influxdb и Chronograf.

Создал в Influxdb конфиг для Telegraf. Внёс правки в docker compose Telegraf.

Создал в Chronograf дашборд с метриками по ресурсам машины, mysql, nginx, также добавил код http ответа от CMS.

Настроил в Chronograf отправку алертов о чрезмерном потреблении ресурсов, падении mysql и 500х ошибках в telegram.

