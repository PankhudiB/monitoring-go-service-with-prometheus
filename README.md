# monitoring-go-service-with-prometheus
This repository spins up Prometheus to monitor a golang web-service that has prometheus client instrumentation.

Prometheus is running on port 9090
Golang web service is running on port 8090

Steps to run
cd to monitoring-go-service-with-prometheus directory
run `docker-compose up`
hit `localhost:9090` in browser to see prometheus dashboard and monitor metrics of go service
