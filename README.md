# Docker Environment
` Docker Enviourment for run mutliple enviourment instance in same machine`

# Installation
- [Install Docker](https://www.docker.com/)
    - [Installation Guideline](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-18-04)
- [docker-compose](https://docs.docker.com/compose/) 
    ```
    sudo apt install docker-compose
    ```
#### Run commands after clone project for each service (such as commonService, php8apps, php7apps etc)

*To build and run docker image*
```
docker-compose up --build
```

# How to run a project


```
syntax: docker-compose run -rm -pDockerport:ExternalPort service-name bash
```

```
example: docker-compose run --rm -p8700:8000 php8apps bash 
```
