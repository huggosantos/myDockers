
[![Docker Pulls](https://img.shields.io/docker/pulls/huggosantos/smartgit.svg?style=flat-square)](https://links.ifbaeunapolis/huggosantos/smartgit)


# Smart Git 7.1.2


### Pull da imagem no Docker Hub
```
docker pull huggosantos/smartgit
```
 

## RUN linux

Rodar esse comando primeiro caso a distribuição seja ubuntu. 
```
xhost +local:docker
```

### Run image
```
 sudo docker run -it --env="DISPLAY" --workdir="/home/$USER" --volume="/home/$USER:/home/$USER" --volume="/etc/group:/etc/group:ro" --volume="/etc/passwd:/etc/passwd:ro" --volume="/etc/shadow:/etc/shadow:ro" --volume="/etc/sudoers.d:/etc/sudoers.d:ro" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" --name smartgit huggosantos/smartgit


 
