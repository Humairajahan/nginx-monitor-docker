# nginx-monitor-docker

This repository aims at scraping an nginx server and showing the scraped metrics in grafana. We do this by using an nginx-prometheus-exporter which listens to the nginx and passes the metrics in prometheus's format to Prometheus and then call up prometheus as a data source in grafana. 

<!-- ![alt text](/images/Screenshot%20from%202022-12-29%2016-50-09.png) -->