FROM node:22-alpine

RUN apt-get update && \
    apt-get install -y openssh-client && \
    rm -rf /var/lib/apt/lists/*
    
RUN apk add --no-cache \
    docker-cli \
    openssh-client

WORKDIR /workspace