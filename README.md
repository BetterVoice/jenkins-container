Jenkins Dockerfile
==================

This project can be used to deploy a Jenkins server inside a Docker container. The container also has git, node package manager, grunt and bower installed.

#### Starting the container.

```
sudo docker run -p=8080:8080/tcp -i -t bettervoice/jenkins:1.0
```
