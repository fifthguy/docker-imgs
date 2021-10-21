# DOCKERFILE for spades
FROM ubuntu:16.04
MAINTAINER Tomaz M. Zorec, tomaz-mark.zorec@mf.uni-lj.si

RUN apt-get update && apt-get -y install \
	bash \
	python \
	python3 \
	wget


WORKDIR /NGStools

RUN wget https://cab.spbu.ru/files/release3.15.3/SPAdes-3.15.3-Linux.tar.gz && tar -xf SPAdes-3.15.3-Linux.tar.gz 

ENV PATH="/NGStools/SPAdes-3.15.3-Linux/bin:$PATH"
