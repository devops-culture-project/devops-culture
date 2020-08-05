# CI/CD for Docker
In this lab we will create an entire environment of developement.
We will create a basic ci/cd for docker that will build the image and push it to your docker hub account.

## Requirements
This lab assumes that you are running on a linux machine (MACOS is also good).
Please install theese softwares on your machine/workstation:
1. docker 
1. docker-compose

## Environment
This is your working directory for this lab (Labs/ci-cd-docker).
Please ensure that jenkins_home directory is exists and empty.

1. Attached there is a docker-compose.yml file. It will set up your Jenkins server.
1. On your own:
1. 1. Look at the compose file and see whats inside.
1. 1. Find the address that jenkins will listen to.
1. run in the working directory: `docker-compose up -d`