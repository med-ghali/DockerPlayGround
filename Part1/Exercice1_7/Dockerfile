FROM ubuntu:20.04

RUN apt-get update && apt-get install -y \
	curl \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /home

COPY script.sh .

RUN chmod -u+x script.sh

CMD ./script.sh