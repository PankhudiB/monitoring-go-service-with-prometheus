# monitoring-go-service-with-prometheus
This repository spins up Prometheus to monitor a golang web-service that has prometheus client instrumentation.

* `Prometheus` is running on port `9090`. 
    - Scrapes the go web service on the interval of every 5 seconds
* `Golang web service` is running on port `8090`.
    - Exports custom metric called `incoming_requests_metric` other than default metrics
* Both Prometheus and go web service are containerized

Steps to run
1. cd to monitoring-go-service-with-prometheus directory
2. run `docker-compose up`
3. hit `localhost:9090` in browser to see prometheus dashboard and monitor metrics of go service
