# Elastic stack (ELK) with Kafka pipeline to analyze log apache on Docker
![](https://miro.medium.com/fit/c/1675/501/0*TEPjqgWDVCk5zn5i.png)

## Run mini datalake
```
docker-compose -f docker-compose.yml up -d
```

## Pay attention for MD5 branch
```
unzip logstash/file/network_traffic_data.zip
mv network_traffic_data.json logstash/file
docker-compose up -d
```

## How is application:
- kibana: localhost:5601

username: elastic
userpassword: changeme
