FROM jenkins/jenkins:lts-jdk11

LABEL maintainer="ben29774583@gmail.com"

USER root

RUN apt-get upgrade -y\
    && apt-get update -y\
    && apt-get install yamllint -y
