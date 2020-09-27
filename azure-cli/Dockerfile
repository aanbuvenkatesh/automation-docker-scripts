FROM ubuntu:latest

WORKDIR usr/src/app

RUN apt-get update -y \
&& apt install maven -y \
&& DEBIAN_FRONTEND="noninteractive" apt-get -y install tzdata \
&& apt-get install python3 -y \
&& apt-get install python3-pip -y \
&& python3 -m pip install decorator \
&& apt-get install azure-cli -y
