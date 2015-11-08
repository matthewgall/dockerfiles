FROM gliderlabs/alpine:latest
MAINTAINER Matthew Gall <docker@matthewgall.com>

RUN apk add --update \
	python \
	python-dev \
	py-pip \
	py-virtualenv \
	build-base \
	&& rm -rf /var/cache/apk/*