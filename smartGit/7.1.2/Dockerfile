FROM huggosantos/jdk8
MAINTAINER Huggo Santos Oliveira <huggo.oliveira1@gmail.com>

USER root
RUN apt-get install -y xorg
RUN apt-get install -y git
RUN apt-get install -q -y axel
RUN axel http://www.syntevo.com/static/smart/download/smartgit/smartgit-linux-7_1_2.tar.gz
RUN tar -vzxf smartgit-linux-7_1_2.tar.gz

CMD /smartgit/bin/smartgit
