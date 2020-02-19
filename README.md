# sf-rampup
The idea of this rampup is to learn the basic tools needed to start working in the SF project
## Pre-requisit
* Have an aws account
* Have a Github account
* Install [terraform](https://learn.hashicorp.com/terraform/getting-started/install.html)
* Install [ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
* Install [packer](https://packer.io/docs/install/index.html)

## Exercise 1
* Create an ansible script using packer capable of creating a Jenkins instance VM
* Create a terraform deploy capable of deploying Jenkins instance in aws in high availability

## Exercise 2
* Create a github repository 
* Upload the test app https://github.com/acalder88/springboot into it
* Create a jenkins multi-branch pipeline which will be triggered by a webhook
* Create a Jenkins file which will build the test app, run the tests, package it into a docker image and publish it into a docker repository (ECR recommended)

## Exercise 3
* Create a terraform deploy capable of creating an EKS cluster in aws
* Install [eksclt](https://eksworkshop.com/030_eksctl/prerequisit)
* Complete this tutorial [eks/beginner](https://eksworkshop.com/beginner/)

## Exercise 4
* Add an step to the pipeline created in Exercise 2, which will deploy the docker image into the EKS cluster using helm in high availability
* Enable the test app to be accesed from the internet

