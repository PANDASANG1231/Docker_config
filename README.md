# Docker configuration with CI

Author: Wenjia Zhu

Personal template for maintaining a docker repository on DockerHub. 

### About

Personal template for maintaining a docker repository on DockerHub. With the help of Github Actions, every change in Dockerfile will be updated to the docker repo in DockerHub. Click here to install [Docker](https://www.docker.com/get-started). And to pull the image [python_env](https://hub.docker.com/repository/docker/zwj63518583/python_env) from Docker Hub.

### Usage

#### 1\. Updating Docker

Change the `Dockerfile`, and Github Actions will do the updating things automatically.

#### 2\. Using Docker

```
docker pull joshsia/markov-language-model
```
