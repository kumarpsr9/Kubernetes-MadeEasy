
# Kubernetes - Made Easy
### Kubernetes Deployment for Nginx With Persistent Volume Mount 

Kubernetes is a powerful container orchestration platform that allows developers to deploy and manage containerized applications at scale. However, managing Kubernetes resources can be complex and time-consuming, especially for teams that are new to the platform.

#### Clone Repository 
`$ git clone  git@github.com:kumarpsr9/Kubernetes-MadeEasy.git`

#### Run Deployment
`kubectl apply -f .`

#### Note: change **PATH** in **PersistentVolume.yml** file to your working directory

path: "**<PATH>** /Kubernetes-MadeEasy/html"


#### To Test Nginx Browse 
`http://localhost:30145/`