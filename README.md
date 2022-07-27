# Udacity: Auto-deploying a Web App

This repository contains solution to the project "Give Your Application Auto-Deploy Superpowers" of my Udacity Cloud DevOps Nanodegree Program
<p align="left">
A CI-CD pipeline for a client/server TypeScript project with backend hosted on AWS EC2 and frontend on AWS S3 bucket and served via CloudFront, monitored with Prometheus with Slack used for alerts. AWS Infrastructure created with Cloud Formation Templates, Ansible used in server configuration and Prometheus configuration.


## Prerequisites

* [Nodejs 13](https://nodejs.org/en/)
* [Docker](https://www.docker.com/)
* [GitHub account](https://github.com/)
* [CircleCi account](https://circleci.com/)
* [AWS account](https://aws.amazon.com/)
* [kvdb api bucket](https://kvdb.io/)
* [Slack api App and Workspace](https://slack.com/)

## Project files
Relevant project files

* [Frontend Folder](./frontend/) : Contains the frontend files of the application, access the [README](./frontend/README.md) on how to use locally

* [Backend Folder](./backend/) : Contains the backend files of the application, access the [README](./backend/README.md) on how to use locally

* [Circleci Folder](.circleci): Contains the circleci [config file](.circleci/config.yml) for the CI/CD pipeline as well as the [ansible folder](.circleci/ansible/) with the different playbooks for server configuration. The [files folder](.circleci/files/) contains the cloud formation templates for AWS infrastructure provisioning.
  
