# Домашнее задание к занятию «ELK» Павлов Дмитрий  

## Задание 1. Elasticsearch  
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.  
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.  
## Решение  
![скриншот к заданию 1](/pic/pic01.png)

## Задание 2. Kibana  
Установите и запустите Kibana.  
Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.  
## Решение  
![скриншот к заданию 2](/pic/pic02.png)

## Задание 3. Logstash  
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.  
## Решение  
![скриншот к заданию 3](/pic/pic03.png)

## Задание 4. Filebeat.  
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.  
Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.  
## Решение  
![скриншот к заданию 4](/pic/pic04.png)