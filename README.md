
# Kubernetes - Made Easy
### Kubernetes Deployment for Nginx With Persistent Volume Mount 

Kubernetes is a powerful container orchestration platform that allows developers to deploy and manage containerized applications at scale. However, managing Kubernetes resources can be complex and time-consuming, especially for teams that are new to the platform.

## Basic Components
- Deployment with 2 Replicas 
- Service
- Storage Class
- Persistent Volume
- Persistent Volume Claim


### Clone Repository 
`$ git clone  git@github.com:kumarpsr9/Kubernetes-MadeEasy.git`

### Prerequisite
Install Minkube 


### Run Deployment
`kubectl apply -f .`

#### Note: change **PATH** in **PersistentVolume.yml** file to your working directory

path: "**<PATH>** /Kubernetes-MadeEasy/html"


### To Test Nginx Browse 
`http://localhost:30145/`

## Screenshot

![Test Page](https://raw.githubusercontent.com/kumarpsr9/Kubernetes-MadeEasy/main/html/screenshot.png)

