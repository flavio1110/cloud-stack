FROM ubuntu:16.04
#https://hub.docker.com/r/flavio1110/ubuntu-util/

LABEL maintainer "Flavio Silva <flavio1110@gmail.com.com>"

RUN apt-get update \
    && apt-get install -y ssh gettext \
    && rm -rf /var/lib/apt/lists/* /tmp/*