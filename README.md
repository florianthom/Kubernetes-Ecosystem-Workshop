# Kubernetes Presentation

in-depth introduction to Kubernetes with detailed insights (in german)

## Learned
* minikube
* kubectl
* Kubernetes Infrastructure
* Kubernetes Objects (with Manifest-Files)
    * Pod
    * Deployment (and diffrence to ReplicaSets)
    * Service
    * PersistentVolume
    * PersistentVolumeClaim
    * most of scaling-possibilities (HPA,VPA,CA)
    * Secrets, ConfigMaps, ...

## Prerequisites
if you want to rebuild my own example (= little httpd-server with only one index.html page)
* Kubernetes Cluster (or something like minikube)
* kubectl (connected to cluster)
* Docker

## Setup
* kubectl apply -f ./example/httpd/kube_files/boundledtogether/httpd-dev-manifest.yaml

## TL;DR:
## Build with
* minikube
* Docker

## Acknoledgements
* Dr. Patrick Fuhrmann (part of DESY: physics computing group) for the BigData-course, related course-work and the possibility to present my results
