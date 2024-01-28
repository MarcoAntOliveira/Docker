FROM ubuntu:18.04

ENV TZ =America/Santa_Catarina
RUN ln -snf /usf/share/zoneinfo/STZ /etc/localtime &&echo STZ >/etc/timezone

RUN apt update && apt install -y curl git unzip xz-utils zip lbglu1-mesa openjdk-8-jdk

RUN  useradd -ms /bin/bash developer
USER developer
WORKDIR /home/developer