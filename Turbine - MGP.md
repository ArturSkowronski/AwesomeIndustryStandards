# Turbine MGP

## Industry
* Games, Mobile Games

## Infrastructure
* Amazon Web Service

### Tenancy
* Mutlitencancy 

### Adressing
* Route 53 DNS

### Provisioning
* Config in Consul with Confd (https://github.com/kelseyhightower/confd)
* Immutable Infrastructure 
* CoreOS
* Fleet
* etcd
* Any service can show up on any port

### Containers
* Event Third Party are stored in Containers
* Tiny Containers without OS specific things
* Build Containers with every commit
* Deploy by GitSHA
* Drop all capabilities
* Sideckick - Additional Containers for additional services to make container Env Agnostic - For Example Enginx, Load Ballancing 

### Security 
* Keys changed with Every Deployment

### High Availability
* Amazon Availability Zones

### Isolation from Internet
* VPC 

### Load Ballancing
* Elastic Load Ballancings

### DB 
* Datastore Per Service

### Integration
* Contracts
* Consul

### Server
* Nginx

### Metrics 

## Technologies
* Go
* Docker
* CoreOS
* Kafka

### Source Controll
* GIT

## Scaling

## Log
* Client send data to Kafka
* Analytics consume from Kafka which let them consume data as they want
* 200k request per second

## Communication
* Hipchat

AWS re:Invent 2015 | (GAM402) Turbine: A Microservice Approach to Three Billion Game Requests a Day
https://www.youtube.com/watch?v=txJmBA4cdQM