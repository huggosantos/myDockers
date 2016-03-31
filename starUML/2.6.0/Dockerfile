FROM ubuntu:14.04

RUN apt-get update && apt-get install -q -y axel xorg unzip dpkg

RUN axel http://staruml.io/download/release/v2.6.0/StarUML-v2.6.0-64-bit.deb
RUN dpkg -i StarUML-v2.6.0-64-bit.deb


CMD /opt/staruml/startuml
