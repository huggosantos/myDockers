FROM ubuntu:14.04
MAINTAINER Huggo Santos Oliveira <huggo.oliveira1@gmail.com>


RUN apt-get update 
RUN apt-get install -q -y axel
RUN axel https://download.sublimetext.com/sublime-text_build-3103_amd64.deb
RUN dpkg -i sublime-text_build-3103_amd64.deb

CMD sublime-text
