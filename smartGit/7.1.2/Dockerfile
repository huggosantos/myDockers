FROM huggosantos/jdk8
MAINTAINER Huggo Santos Oliveira <huggo.oliveira1@gmail.com>

USER root
RUN apt-get update && apt-get -y install \ ca-certificates  \ libglib2.0-0 \ libx11-6 \ libcairo2 \ libpango-1.0-0 \ libpangocairo-1.0-0 \ libgtk2.0-0 \ --no-install-recommends \ && rm -rf /var/lib/apt/lists/*
RUN apt-get install -y git
RUN apt-get install -q -y axel
RUN axel http://www.syntevo.com/static/smart/download/smartgit/smartgit-linux-7_1_2.tar.gz
RUN tar -vzxf smartgit-linux-7_1_2.tar.gz

CMD /smartgit/bin/smartgit
