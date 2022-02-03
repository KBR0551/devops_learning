# devops_learning
Using Terraform to spin up Azure AKS cluster and deploy a MySql Database container and Spark container and load data to MySql Database using PySpark


# Overview

A project to demonstrate:

  Building a simple PySpark Application to load Data to Mysql Database.
  Containerse PySpark Application Using Docker and push to GitLab Container registery
  Pull Mysql image from Docker Hub
  Cretae Kubernetes YAML files for (Pods, Stateful Sets, Secrets, Services, PV, PVC etc.,) 
  Leverage Helm Charts to package YAML files to deployed on kubernetes
  Deploy Helm charts on Kubernetes Minikube to verify things work as expected
  Create CI/CD pipeline to build Azure Kubernetes Service (AKS) Infrastructute using Terraform, spin Up MySql Database and Deploy Pyspark application
  Automated build & deployment using Gitlab CI/CD
  Troubleshooting and issues faced.
