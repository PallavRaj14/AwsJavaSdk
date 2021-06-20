#Introduction

#Minio 

Minio is cloud object storage server compatible with Amazon S3.
Minio as Object store can store unstructured data such as photos, vidios, log files, backups and container images.

#Docker

Here Docker plays important role to deploy Minio.
Download Docker image for Minio.

#Notes:

I am using Docker-Machine and Docker-Compose, So Docker-Compose.yaml file is attached in project.
For this you just need to install Docker on your PC and install Docker-Machine and docker-compose up to deploy minio.

Procedure to deploy application.
- Install Docker image of Minio/OR Docker Machine, and can use my Docker Compse to use Minio
- In application.properties(http://docker:9000/) file in place of docker you may use your Docker-Machine IP. 
