# DevOps Challenge

## Goal
The challenge goal is to build an infrastructure for a kafka producer and consumer.

## Context
We provide a simple Kafka producer and consumer service.
- Producer will send a message to Kafka every second.
- Consumer is responsible for receiving these messages.

The application is written in GO and will need a Kafka service.

## Task
The task is to deploy the application on a Kubernetes Cluster.
* Make sure to minimize manual operations and use any automation tools you might know.
* Review your solution and ensure it follows the best practices of building and deploying microservices.
* Prepare a detailed document and/or instructions about what you have done. These documents must detail steps for other DevOps engineers to understand how to deploy and maintain this application.

## Instructions
- Using Terraform, build the infrastructure resources.
- Build a Kubernetes Cluster in a private network, you can use any tools todo this. This cluster can be setup locally or in the cloud.
- You can either use a managed or a self-hosted solution to provision the Kafka service.
- You may need to modify the application source code or configuration in order to make the application running on the Kubernetes cluster.
- You need to update the application dependencies to last stable and compilable version.

### How to proceed
1. Clone this repository on your local machine and start a new local repository.
2. Write the code.
3. Write the documentation.
4. The repository should contain the modified application and all other DevOps files and scripts in a separate folder.
5. Create a repository on Github/Gitlab and push your code on it.

## Extra Credit
* Monitoring Implementation
* Autoscaling Consumers
* Helm Charts to manage producer/consumer services.