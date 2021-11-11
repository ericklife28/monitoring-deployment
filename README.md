## You need to provide permisions for the user 472 and 473

sudo chown -R 472:472 /var/grafana_data

sudo chown -R 473:473 /var/prometheus_data


## Load Test

ab -n 1000000 -c 10 http://petclinic-app:8080/