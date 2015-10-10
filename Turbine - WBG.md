#Turbine WBG

## Industry
* Games, Mobile Games

## Infrastructure
* Amazon Web Service

### Adressing
They have own standard of building server adressing which let them know what is a role of given adress and from which cloud it is

### Provisioning
Chef
Baked AMI with whole App Layer (Proxy, RabbitMQ, Services) - X Scalling, Lack of Coarce

### High Availability
Amazon Availability Zones

## Security
* Each game has different Virtual Private Cloud [http://docs.aws.amazon.com/AmazonVPC/latest/UserGuide/VPC_Introduction.html], and has access just to it's resources and internal Turbine Services. 

### Load Ballancing
* Elastic Load Ballancings

### Metrics 
* Amazon CloudWatch
* Statsd protocol (https://github.com/etsy/statsd)
* Librato (https://www.librato.com/)
* Don't know what to measure, measure everything

## Technologies
RabbitMQ, Kafka, Chef, Redis (with Elastic Cache), MongoDB

## Scaling
### Pre-emptive AWS capacity planning
* Prewarming ELB
* Amazon Elastic Block Store limit 192TB GP2

* Don't know how to scale RabbitMQ
* Everything goes through RabbitMQ to Mongo

## Log
* Services fire events which are stored to Mongo
* Daily Dump
* Single MongoDB 

AWS re:Invent 2015 | (GAM402) Turbine: A Microservice Approach to Three Billion Game Requests a Day
https://www.youtube.com/watch?v=txJmBA4cdQM