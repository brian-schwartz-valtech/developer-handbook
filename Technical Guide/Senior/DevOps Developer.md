DevOps Developer
================

DNS
---

*   [ ] You know what a CNAME record is and when to use it
*   [ ] You know what an A and AAAA records are and when to use them
*   [ ] You know what TXT records is and when to use it
*   [ ] You know how to register a new domain with a chosen DNR
*   [ ] You know how to switch NS from default ones set by DNR to another provider
*   [ ] You know what a MX record is and when to use it

### [DNS Services](/Technical%20Stack/DevOps%20Developer/DNS.md#dns-services)

#### [Route 53](/Technical%20Stack/DevOps%20Developer/DNS.md#route-53)

*   [ ] You know how to define a new hosted zone
*   [ ] You can create DNS records using AWS CLI

#### [Cloudflare](/Technical%20Stack/DevOps%20Developer/DNS.md#cloudflare)

*   [ ] You know how to define a new DNS zone
*   [ ] You can create DNS records using Cloudflare API

Databases
---------

### [SQL](/Technical%20Stack/DevOps%20Developer/Databases.md#sql)

#### [AWS RDS](/Technical%20Stack/DevOps%20Developer/Databases.md#aws-rds)

*   [ ] You know how to instantiate a PostgreSQL database
*   [ ] You know how to instantiate a MySQL database
*   [ ] You know how to instantiate an AWS Aurora instance with chosen DB flavour

### [NoSQL](/Technical%20Stack/DevOps%20Developer/Databases.md#no-sql)

#### [Redis](/Technical%20Stack/DevOps%20Developer/Databases.md#redis)

##### [AWS ElastiCache](/Technical%20Stack/DevOps%20Developer/Databases.md#aws-elasti-cache)

*   [ ] You know how to create a Redis instance
*   [ ] You know how to connect to Redis instance from the application code

#### [ElasticSearch](/Technical%20Stack/DevOps%20Developer/Databases.md#elastic-search)

##### [AWS Elasticsearch Service](/Technical%20Stack/DevOps%20Developer/Databases.md#aws-elasticsearch-service)

*   [ ] You know how to create an ElasticSearch instance
*   [ ] You know how to connect to ElasticSearch from the application code

#### [AWS DynamoDB](/Technical%20Stack/DevOps%20Developer/Databases.md#aws-dynamo-db)

*   [ ] You know how to manage dynamodb read/write throughput
*   [ ] You know how to configure pay per use model

Contenerization Services
------------------------

### [AWS ECS](/Technical%20Stack/DevOps%20Developer/Contenerization%20Services.md#aws-ecs)

*   [ ] You know how to create a task definition
*   [ ] You know how to execute a one off task that is killed after execution and doesn't get restarted
*   [ ] You know how to define a service
*   [ ] You know how to create a target group pointing to your ECS service and add it to an Application Load Balancer listener

### [Kubernetes](/Technical%20Stack/DevOps%20Developer/Contenerization%20Services.md#kubernetes)

*   [ ] You know how to define a deployment entity

Application Servers
-------------------

### [Nginx](/Technical%20Stack/DevOps%20Developer/Application%20Servers.md#nginx)

*   [ ] You know configuration file syntax
*   [ ] You know how to serve static files
*   [ ] You know how to define a proxy pass to API server

### [WSGI](/Technical%20Stack/DevOps%20Developer/Application%20Servers.md#wsgi)

*   [ ] You know how to deploy a wsgi app (django, flask) with one of the application servers
*   [ ] You know wsgi configuration file syntax

Task Queues
-----------

### [Celery](/Technical%20Stack/DevOps%20Developer/Task%20Queues.md#celery)

*   [ ] You can choose one of the message brokers and configure Celery to use it
*   [ ] You can deploy Celery workers to at least one platform of your choice

Message Brokers
---------------

### [RabbitMQ](/Technical%20Stack/DevOps%20Developer/Message%20Brokers.md#rabbit-mq)

*   [ ] You understand what a virtual host is and how to create one
*   [ ] You can deploy RabbitMQ to AWS platform
*   [ ] You understand what a Routing Key is
*   [ ] You understand what an Exchange is and you can describe common types of exchanges (direct, topic, fanout)
*   [ ] You understand what a Channel is and how is it used in message flow

### [AWS SQS](/Technical%20Stack/DevOps%20Developer/Message%20Brokers.md#aws-sqs)

*   [ ] You know how to create an SQS queue
*   [ ] You can attach Lambda function trigger to a queue
*   [ ] You know how to use the concept of dead letter queues to repair broken messages

### [AWS EventBridge](/Technical%20Stack/DevOps%20Developer/Message%20Brokers.md#aws-event-bridge)

*   [ ] You can create an EventBus
*   [ ] You can send custom events to an EventBus
*   [ ] You know how to trigger a Lambda function from an EventBus for a specific event source

### [AWS Kinesis](/Technical%20Stack/DevOps%20Developer/Message%20Brokers.md#aws-kinesis)

*   [ ] You know what a Kinesis Stream is and can name some use cases
*   [ ] You know what a shard is in Kinesis Stream context
*   [ ] You know how to trigger a Lambda function from a Kinesis Stream

Generic AWS Services
--------------------

### [VPC](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#vpc)

*   [ ] You know how to create a VPC
*   [ ] You understand the concept of Subnets and know how to create one
*   [ ] You understand the concept of Security Groups, know how to create one and how to define its rules
*   [ ] You know what a NAT Gateway is (and how much it costs)
*   [ ] You know what a VPC Endpoint is and how to define it
*   [ ] You know how to create a NAT Gateway

### [EC2](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#ec2)

*   [ ] You know how to create an EC2 instance
*   [ ] You know how to SSH into an EC2 instance using generated key pair
*   [ ] You know how to create an Application Load Balancer
*   [ ] You know how to attach a Security Group to an instance

### [IAM](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#iam)

*   [ ] You know how to create a new user
*   [ ] You know how to create a new role
*   [ ] You know how to create a policy documents and attach them to various IAM resources
*   [ ] You know how to configure a "switch role" method so the user from one account can log into another role from another account

### [KMS](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#kms)

*   [ ] You know how to create a KMS key and assign alias to it

### [SSM](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#ssm)

*   [ ] You know how to create an SSM parameter and encrypt it with a KMS key
*   [ ] You know how to use SSM parameter in Lambda function

### [AWS Client libraries](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#aws-client-libraries)

#### [aws-cli](/Technical%20Stack/DevOps%20Developer/Generic%20AWS%20Services.md#aws-cli)

*   [ ] You know how to create a local profile using acquired key id and secret to access AWS resources

Storage
-------

### [AWS S3](/Technical%20Stack/DevOps%20Developer/Storage.md#aws-s3)

*   [ ] You know how to create an S3 bucket
*   [ ] You know how to make a S3 bucket public
*   [ ] You know how to host a Single Page Application in S3

Continuous Integration
----------------------

### [Bitbucket Pipelines](/Technical%20Stack/DevOps%20Developer/Continuous%20Integration.md#bitbucket-pipelines)

*   [ ] You know how to turn Bitbucket pipelines on in a repository
*   [ ] You know how to run a pipeline execution after a commit or a tag push
*   [ ] You know how to define environmental variables that will be available to a build script

### [Github Actions](/Technical%20Stack/DevOps%20Developer/Continuous%20Integration.md#github-actions)

*   [ ] You know how to define a workflow
*   [ ] You know how to run a workflow execution after a commit or a tag push
*   [ ] You know how to define environmental variables that will be available to a build script

### [AWS CodePipeline](/Technical%20Stack/DevOps%20Developer/Continuous%20Integration.md#aws-code-pipeline)

*   [ ] You know how to create a CodePipeline
*   [ ] You know how to define a build step using CodeBuild
*   [ ] You know how to connect CodePipeline to an S3 source so the execution starts when a file changes
*   [ ] You know how to connect CodePipeline to a CodeCommit repository so the execution starts when branch or tag has been pushed
*   [ ] You know how to connect CodePipeline to a custom repository (Github, Bitbucket) so the execution starts when branch or tag has been pushed
*   [ ] You know how to define environmental variables that will be available to a build script
*   [ ] You know how to assign a custom IAM role to the build executor so it can access AWS resources
*   [ ] You know how to run a lambda function as a build step

CDN
---

### [AWS CloudFront](/Technical%20Stack/DevOps%20Developer/CDN.md#aws-cloud-front)

*   [ ] You know how to create a CloudFront distribution
*   [ ] You know how to add a behaviour pointing to an S3 website bucket

### [Netlify](/Technical%20Stack/DevOps%20Developer/CDN.md#netlify)

*   [ ] You know how to create an app
*   [ ] You know how to create a custom domain for an app
*   [ ] You know how to define environmental variables available during build step

Docker Registry
---------------

### [AWS ECR](/Technical%20Stack/DevOps%20Developer/Docker%20Registry.md#aws-ecr)

*   [ ] You know how to create a registry
*   [ ] You know how to upload a Docker image to a registry
*   [ ] You know how to define an IAM policy of a registry to allow pull/push to a specific user or role
*   [ ] You know how to log into the ECR registry using aws-cli

VPS Services
------------

### [DigitalOcean](/Technical%20Stack/DevOps%20Developer/VPS%20Services.md#digital-ocean)

*   [ ] You know how to create a droplet in chosen region

### [AWS EC2](/Technical%20Stack/DevOps%20Developer/VPS%20Services.md#aws-ec2)

*   [ ] You know how to create an instance in a chosen region

Monitoring
----------

*   [ ] Work in progress

* * *

Contribution
------------

We are very open to contributions to extend or change the requirements based on your gut and experience. To contribute you can use a **pull request** which will be later validated by our technical team and added to the main docs.

If you will spot any issues please add them in the **Issues** section.

Credits
-------

This page is maintained by the 🔹 [Flairs.ai](http://Flairs.ai) and 🇵🇱 [Apptension](https://apptension.com) teams.

If you would like to create a dedicated Developer Handbook for your company, you can e-mail us 👉 [contact@flairs.ai](mailto:contact@flairs.ai)

License
-------

![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)

© 2020 Flairs Sp. z o.o.

Built and maintained by [Flairs](https://www.flairs.ai) and [Apptension](https://apptension.com).

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.