```
docker-compose up setup
docker-compose -f docker-compose.yml -f extensions/filebeat/filebeat-compose.yml -f extensions/metricbeat/metricbeat-compose.yml up -d

docker-compose ls
sudo docker-compose -p docker-elk ps -a
```