# Red Hat AMQ Streams Overview


## Purpose
The demo shows the use of AMQ Streams from an operation and development perspectives.  
It complements AMQ Streams with other elements of the Application Foundation portfolio to create a more holistic soltion.  
It addition, it demonstrates a full-scale install of the entire solution as code.

### Operational perspective
From the Operational perspective, the demo particularly highlights :  
 - Operating with the AMQ Streams Operator
 - Performing operations as code
   * Managing Users and Topics
   * Scaling up and down
   * Performing zero-downtime upgrade
 - Keeping a close eye on consumer lagging time
 - Securing the platform with OIDC

### Development perspective
 From the Development perspective, the demo is arcticulated around 2 cases.  
 
 The first case highlights : 
 - Using Debezium for CDC, leveraging KafkaConnect to query events from a Postgres database
 - Integrating the data with ElasticSearch using CamelK

 The second cases highlights:  
 - Using Quarkus reactive clients
 - Leveraging Red Hat Service Registry to exchange Avro data
 - Propagating business information via traces

## Demo workflow
The overall workflow involves 2 roles: a developer and an operator.  

The operator will start by performing the initial operations:
- Installing and configuring the AMQ Streams cluster
- Securing the cluster

The developer will continue with the below activities:
- Integrating data in and out of the AMQ Streams cluster
- Updating the code and the data
- Exposing tracing information

Finally, the operator will perform day2 operations such as:
- Monitoring the performance
- Scaling the cluster up or down
- Upgrading the cluster


![workflow](documentation/images/general_scenario.png?raw=true)

## Installation
### Developer's cases

[developer install 1](documentation/developer_i1.md)  
[developer install 2](documentation/developer_i2.md)  
  
### Operator's cases

[Operator install_1](documentation/operator_i1.md)  
[Operator install_2](documentation/operator_i2.md)  


## Scenario
### Developer's cases

[developer case1](documentation/developer_s1.md)  
[developer case2](documentation/developer_s2.md)  
  
### Operator's cases

[Operator day1](documentation/operator_s1.md)  
[Operator day2](documentation/operator_s2.md)  
