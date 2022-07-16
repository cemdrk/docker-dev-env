FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install python3 -y

RUN useradd -m ubuntu -G sudo -s /bin/bash
RUN echo "ubuntu:ubuntu" | chpasswd

USER ubuntu
WORKDIR /app
