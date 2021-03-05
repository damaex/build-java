FROM ubuntu:18.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update

# install tools
RUN apt-get -y install git wget curl unzip zip apt-transport-https ca-certificates

# install compiler and compilation-tools
RUN apt-get -y install default-jdk