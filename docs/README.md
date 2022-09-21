# Introduction

## Getting Started with Kubernetes on the IBM Cloud

Welcome to my guide for using Kubernetes on the IBM Cloud. In this guide I will provide a high level overview of what Kubernetes is, its main components and then move on to practical examples of how to do the following:

* Deploy am IKS Cluster using the IBM Cloud CLI
* Install managed add-ons in the cluster 
* Deploy a simple httpbin app using kubectl
* Expose the httpbin app with LoadBalancer and Ingress services
* Test autoscaling of pods 
* Explore logging and monitoring services for the cluster 

### About this Guide

The introductory page of this guide is broken down into the following sections:

* [Agenda](./#agenda)
* [Compatibility](./#compatibility)
* [Technology Used](./#technology-used)
* [Credits](./#credits)

## Agenda

|  |  |
| :--- | :--- |
| [0: Pre-work](pre-work/README.md) | Pre-work for the guide |
| [1: Kubernetes-Overview](01-kubernetes/README.md) | Overview of Kubernetes and IKS |
| [2: Deploy-IKS](02-deploy-iks/README.md) | Deploy an IKS cluster using Cloud Shell |
| [3: Install Managed Add-ons](03-add-ons/README.md) | Deploy and Configure Istio, Autoscaling, etc |
| :--- | :--- |

## Technology Used

* [kubectl][kubectl]: The Kubernetes command-line tool, kubectl, allows you to run commands against Kubernetes clusters.
* [IKS][iks]: IBM Cloud Kubernetes Service (IKS) is a managed offering to create your own Kubernetes cluster of compute hosts to deploy and manage containerized apps on IBM Cloud.
* [IBM Cloud CLI][ibmcloud-cli]: IBM Cloud command line client
* [Cloud Shell][cloud-shell]: A cloud-based shell workspace that you can access through your browser preconfigured with the full IBM Cloud CLI

## Credits

* [Ryan Tiffany](https://github.com/greyhoundforty)


[kubectl]: https://kubernetes.io/docs/tasks/tools/#kubectl
[iks]: https://cloud.ibm.com/docs/containers?topic=containers-iks-overview
[ibmcloud-cli]: https://cloud.ibm.com/docs/cli?topic=cli-getting-started
[cloud-shell]: https://cloud.ibm.com/docs/cloud-shell?topic=cloud-shell-getting-started
