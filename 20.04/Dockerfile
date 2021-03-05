FROM ubuntu:20.04

ARG DEBIAN_FRONTEND=noninteractive

RUN apt-get update

# install tools
RUN apt-get -y install git wget curl unzip zip apt-transport-https ca-certificates

# install compiler and compilation-tools
RUN apt-get -y install default-jdk

# install sdkman
RUN curl -s https://get.sdkman.io | bash
RUN chmod a+x "$HOME/.sdkman/bin/sdkman-init.sh"
RUN source "$HOME/.sdkman/bin/sdkman-init.sh"

# install gradle
RUN sdk install gradle 6.8.3