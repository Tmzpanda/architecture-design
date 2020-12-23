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
 
 



    SOA -> Microservice
               /   \
            SOAP   REST
            RPC    web http
            
```                   
