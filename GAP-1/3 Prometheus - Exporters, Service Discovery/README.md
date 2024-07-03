Используя docker compose, развернул wordpress, образы:
- wordpress:php8.3-fpm-alpine
- mysql:8.0
- nginx:stable-alpine3.17-slim

Также в docker compose развернул prometheus и экспортеры:
- node_exporter
- mysqld-exporter
- blackbox-exporter
- nginx-exporter
- cadvisor