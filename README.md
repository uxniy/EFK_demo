# EFK_demo
#demo for fluentd+elasticsearch+kibana+docker

cd EFK_demo 
docker-compose up -d 
docker ps 
curl localhost:80 
curl localhost:8080 
curl localhost:8070 

http://localhost:5601 

http://localhost:9200/_all/_search?q=* 


