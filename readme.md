# ACME App

This repo demonstrates the use of Kubernetes and Helm in deploying containerized application.

## 1. Create a HELM chart to deploy the application to Kubernetes
- Create the helm chart using the following command:

```
$> mkdir helm
$> cd helm
$> helm create *name of application*
(in this repo, the name of the application is "devops-a3")
```
- Optional step: There are files that will not be used in the directory generated by Helm, we can remove those files using the following commands:
```
$> cd devops-a3
$> rmdir charts
$> rm -rd templates/*
```
- 

