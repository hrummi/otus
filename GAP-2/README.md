Развернул в контейнере Grafana.

Импортировал дашборды для node-exporter, mysqld-exporter, nginx-exporter, blackbox-exporter, cadvisor.

Создал папки infra и app.
На основе дашборда для node-exporter создал в папке дашборд infra_dash.
Используя остальные импортированные дашборды, создал в папке app дашборд app_dash со сводной информацией о CMS.

В Grafana создал алерт на падение MySQL. Использовал метрику mysql_up.