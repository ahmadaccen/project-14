# Project 14 - Application Deployment on Amazon EKS

## Goal

Deploy a containerized application on Amazon Elastic Kubernetes Service (EKS).

## Tasks Completed

- Created EKS Cluster
- Created Managed Node Group
- Configured kubectl access
- Deployed application from Amazon ECR
- Exposed service using Kubernetes LoadBalancer
- Accessed application publicly

## EKS Cluster

Cluster Name:

```text
project14-eks
```

Node Group:

```text
project14-nodes
```

## Container Image

Amazon ECR Image:

```text
590507089733.dkr.ecr.us-east-1.amazonaws.com/project-13-ecr:latest
```

## Kubernetes Deployment

Deployment:

```text
project14-app
```

Service:

```text
project14-service
```

Type:

```text
LoadBalancer
```

## Verification

The Kubernetes service successfully exposed the application through an AWS Load Balancer.

Public Endpoint:

```text
ac6d97451f2324b17b0420a2229d3bca-1519187742.us-east-1.elb.amazonaws.com
```

Application displayed:

```text
Docker Container Running Successfully
Project 8 Completed by Mohammad Ahmad
```

## Deliverable

Public access screenshot showing successful application deployment through EKS.
