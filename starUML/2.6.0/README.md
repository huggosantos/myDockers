[![Docker Pulls](https://img.shields.io/docker/pulls/huggosantos/staruml.svg?style=flat-square)](https://links.ifbaeunapolis/huggosantos/staruml)


# Star UML 2.6.0


### Pull da imagem no Docker Hub
```
docker pull huggosantos/staruml
```
 

## RUN linux

Rodar esse comando primeiro caso a distribuição seja ubuntu. 
```
xhost +local:docker
```

### Run image
```
 sudo docker run -it --env="DISPLAY" --workdir="/home/$USER" --volume="/home/$USER:/home/$USER" --volume="/etc/group:/etc/group:ro" --volume="/etc/passwd:/etc/passwd:ro" --volume="/etc/shadow:/etc/shadow:ro" --volume="/etc/sudoers.d:/etc/sudoers.d:ro" --volume="/tmp/.X11-unix:/tmp/.X11-unix:rw" --name staruml huggosantos/staruml


 
