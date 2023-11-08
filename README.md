# Learning_Jenkins

## Objective

Learn how Jenkins is used in industry
Declarative pipelines
Solid understanding of Jenkins

local pass: adc57321854d46158a2716b63950712a

## Setting up

1. docker run -p 8080:8080 -p 50000:50000 jenkins/jenkins:lts

2. install maven inside the container
   docker exec -it -u root <container id> /bin/bash 
   example: docker exec -it -u root 91796c1f6541 /bin/bash 
