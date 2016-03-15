
FROM huggosantos/jdk8
MAINTAINER Huggo Santos Oliveira <huggo.oliveira1@gmail.com>

USER root

RUN apt-get install -y git
RUN apt-get update 
RUN apt-get install -q -y axel
RUN axel  http://www.syntevo.com/static/smart/download/smartgit/smartgit-7_1_2.deb
RUN dpkg -i smartgit-7_1_2.deb

CMD smartgit
