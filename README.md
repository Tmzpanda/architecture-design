# architecture:


```
Frontend           Backend 


                                           Message queue
                                           Cache
Client ----------> WebServer <-> AppServer <-----> DB
     |             MVC           Microservices     MongoDB
     |                           QuadTree          Elasticsearch                             
     |
      -----------> Kafka -> Spark <--------------> HBase    
                            DevOps
                            CI/CD
                   
```                   
