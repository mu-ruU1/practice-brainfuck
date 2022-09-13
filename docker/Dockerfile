FROM ubuntu

RUN apt-get update && apt-get install -y \
    bf \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /usr/src