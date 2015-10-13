# Netflix

## Industry
* Video

## Infrastructure
* Amazon Web Service

### Tenancy
*  

### Adressing
* 

### Provisioning
* Base AMI

### Containers
* 

### Security 
* 

### High Availability
* Amazon Availability Zones (Three)

### Isolation from Internet
*  

### Resilence
* Chaos Monkey kill instances each day
* Chaos Gorilla kills AZ 
* Chaos Kong kills Region
* Everything visualized in Flux

### Load Ballancing
* 

### DB 
* Datastore Per Service

### Deployment
* Continous Delivery
* https://github.com/Netflix/asgard -> Spinnaker
* Red -> Black Deployments
* Delivery Pipelines
* Small amount of services deploy (canaries), metrics are tested, if better rest of services goes too


### Integration
* Slalom - Tool to showing dependencies between services
* Instances are like plants, not pets - you don't need to name them

### Server

### Metrics 
* Observe, Orient, Decide, Act
* Anomaly Detections - DES Algorithm - http://www.academia.edu/3036168/Genetic_Algorithm_for_Parameter_Estimation_in_Double_ -Exponential_Smoothing
* Predicting what should happend not what happend
* 6-8 Minutes delay, so started streaming
* Few different algorithm check data and vote if there is outage 
* Density based cluster algorithms 
* Kepler, Unsupervised Machine Learnign engine
* Down to 60 s
* Canary - Checking if new version has better metrics than old one
* Flux - visualisation - http://techblog.netflix.com/2015/10/flux-new-approach-to-system-intuition.html
* Show human readable metrics through Mogul

## Technologies
* Gradle
* Ubuntu
* Jenkins
* Spinnaker

### Source Control
* Stash

## Scaling

## Log
* 

## Innner Structure
* Core Team
  * Crisis Menagement
  * Availibility Reporting
  * Reliability Best Practices
  * AWS Relationships
  * Operations Education
  * Protecting Customer Experience 

## Testing 
* 1400 AB Tests last year
* Chaos Engineering - tests in production
* Fault Injection Testing

## Communication

## Cultur
* Team can choose technology
* Team
* 24/7 Call
* Code, Test, Run, Deploy, Support

---------------
Cody Rioux: Netflix Outlier and Anomaly Detection
https://vimeo.com/120851298

AWS re:Invent 2015 | (ISM301) Engineering Netflix Global Operations in the Cloud
https://www.youtube.com/watch?v=IkPb15FfuQU

AWS re:Invent 2015 | (DVO203) A Day in the Life of a Netflix Engineer
https://www.youtube.com/watch?v=-mL3zT1iIKw