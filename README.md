# Foundry VTT Helm Chart

This repository holds a Dockerfile as well as a helm chart that deploys FoundryVTT to a Kubernetes cluster with or without a persistent volume claim.

## Running in Docker



## Building Docker Image Manually

For the Docker Image to build you need to log in to your Foundry VTT and generate a "Timed URL" for Linux. Insert the URL into the Dockerfile (Beware the link is only valid for a couple of minutes) and run

```
 $ docker build -t foundry:latest 
```
 Optionally also run a tag for your version for example: 
```
 $ docker tag foundry:latest foundry:v9-269
```
You can then push this into your registry.
